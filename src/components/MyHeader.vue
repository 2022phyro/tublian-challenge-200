<script setup>
</script>
<template>
    <header>
        <img src="/assets/logo2.png" alt="logo">
        <ul>
            <li class="active">1: Get Started</li>
            <li>2: Create Account</li>
            <li>3: Account Setup</li>
            <li>4: Payment</li>
        </ul>
    </header>
</template>
<style scoped>
header {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    flex-flow: row wrap;
    gap: 25.05px;
    margin-top: 67.5px;
}

header img {
    width: auto;
    height: 24.913px;
}
header ul {
    list-style-type: none;
    display: flex;
    gap: 12px;
    flex-flow: row wrap;

}
header ul li {
    color: var(--base-300-dark, #696969);
/* text-sm/font-medium$ */
    font-family: 'Space Grotesk';
    font-size: 14px;
    font-style: normal;
    font-weight: 700;
    line-height: 20px;
}
.active {
    background: var(--gradient_2, linear-gradient(109deg, #FBDA61 0%, rgba(255, 90, 205, 0.84) 86.08%));
background-clip: text;
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
}
header div {
    display: flex;
    flex-flow: row wrap;
    justify-content: space-between;
    align-items: center;
}
</style>
