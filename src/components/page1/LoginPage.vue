<script setup>
import MyHeader from '../MyHeader.vue';
</script>
<template>
    <section>
    <MyHeader/>
    <h1>Get Started</h1>
    <p class='slogan'>Start recruiting streetcred developers. Today!! </p>
    <form>
        <input type="text" id="first_name" name="first_name" placeholder="First Name">
        <input type="text" id="last_name" name="last_name" placeholder="Last Name">
        <button class="submit">Proceed</button>
    </form>
    <p class="rich-text-login">Already have an account <a>Log in</a></p>
    <p class="privacy"><span>Privacy policy</span><span>Terms</span></p>
</section>
</template>
<style scoped>
section {
    position: relative;
    padding-left: 40px;
}
h1 {
    color: var(--base-900-dark, #FEFEFE);
    margin-top: 40px;
    font-size: 36px;
    font-style: normal;
    font-weight: 700;
    line-height: 52px; /* 144.444% */
}
.slogan {
    color: var(--base-800-dark, #CFCFCF);
    margin-top: 14px;
    font-size: 16px;
    font-style: normal;
    font-weight: 500;
    line-height: 24px; /* 150% */
}
form {
    margin-top: 28px;
    display: flex;
    flex-flow: column;
    width: 405px;
    gap: 28px;
}
input {
    outline: none;
    color: white;
    font-size: 16px;
    font-style: normal;
    font-weight: 500;
    line-height: 24px;
    background: transparent;
    border: none;
    border-bottom: 1px solid var(--base-300-dark, #696969);
    padding: 10px 10px;
}
input::placeholder {
    color: var(--base-300-dark, #696969);
}
.submit {
    display: flex;
    width: 405px;
    padding: 8px 16px;
    justify-content: center;
    align-items: center;
    font-size: 16px;
    font-weight: 500;
    gap: 8px;
    border-radius: 30px;
    background: var(--primary-gold-300, #FDD649);
}
.rich-text-login, .privacy {
    font-weight: 400;
    color: var(--base-800-dark, #CFCFCF);
    font-size: 16px;
    font-style: normal;
}
.rich-text-login {
    margin-top: 28px;
}
.rich-text-login a {
    font-weight: 700;
    color: white;
    text-decoration: underline;
}
.rich-text-login a:hover {
    background: var(--gradient_2, linear-gradient(109deg, #FBDA61 0%, rgba(255, 90, 205, 0.84) 86.08%));
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.privacy {
    display: flex;
    gap: 20px;
    position: absolute;
    bottom: 48px;
}
</style>
