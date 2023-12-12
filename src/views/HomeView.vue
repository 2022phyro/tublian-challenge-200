<script setup>
import LoginPage from '@/components/page1/LoginPage.vue';
</script>

<template>
  <main>
    <div class="decoration">
      <img src="/assets/loginImg.png">
    </div>
    <LoginPage />
  </main>
</template>
<style scoped>
main {
display: grid;
width: inherit;
height: inherit;
grid-template-columns: 50% 50%;
grid-template-rows: 100%;
}
.decoration {
width: 100%;
height: 100%;
padding: 0;
margin: 0;
}
.decoration img{
width: 100%;
height: inherit;
object-fit: contain;
}
@media screen and (max-width: 1000px) {
    main {
grid-template-columns: 100%;
}
.decoration {
display: none;
}

}
</style>
