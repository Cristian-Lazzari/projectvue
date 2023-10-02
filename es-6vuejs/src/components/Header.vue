<script setup>

</script>

<template>
  <div class="header">
    <div class="logo"><img src="https://grace.energy/wp-content/uploads/2022/03/grace-logo.svg" alt=""></div>
    <div class="nav">
        <div class="lang"><a href="#">English</a></div>
        <div class="buy"><a href="#">Buy</a></div>
        <div class="user"><a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
  <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
</svg></a></div>
        <div class="bag"><a href="#"></a></div>
        <div class="menu"><a href="#"></a></div>
        <div class="menu"><a href="#"></a></div>
    </div>
  </div>
</template>

<style scoped lang="scss">
@use "../assets/styles/general.scss";
.header{
    height: 120px;
    background-color: red;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.logo{
    margin: 0px 50px;
}
.nav{
    display: flex;
    gap: 20px;
}
</style>
