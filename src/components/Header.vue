<script setup>

</script>

<template>
  <header>
    <div class="container d-flex">
      <div class="container__logo d-flex">
        <img src="./icons/circle-check-solid.svg" alt="Circle logo">
        <p class="h1__logo"><b>Pomofocus</b></p>
      </div>


      <nav class="container-nav d-flex">
        <div class="container-nav__statistic div__img">
          <img src="./icons/chart-column-solid.svg" alt="" class="img-nav">
        </div>
        <div class="container-nav__options div__img">
          <img src="./icons/gear-solid.svg" alt="" class="img-nav">
        </div>
        <div class="container-nav__account div__img">
          <img src="./icons/circle-user-solid.svg" alt="" class="img-nav">
        </div>
        <div class="container-nav__nav div__img">
          <img src="./icons/ellipsis-vertical-solid.svg" alt="" class="img-nav">
        </div>
      </nav>

    </div>

  </header>
</template>

<style scoped>
.container {
  padding: 10px;
  justify-content: space-between;
}

.container__logo{
  align-items: center;
  gap: 5px;
}

img {
  width: 18px;
  height: 18px;
}

.div__img{
  background-color: var(--Transparent);
  border-radius: 8px;  
  margin: 5px ;
  padding: 8px;
}

.img-nav{
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>