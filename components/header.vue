<template>
  <header>
      <div class="title">blog</div>
    <nav>
        <nuxt-link to="/">Home</nuxt-link>
        <nuxt-link to="/about">About</nuxt-link>
    </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style>
header{
    padding: 10px 30px;
    background-color: burlywood;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0px 3px 6px black;
}
header .title{
    color: brown;
    font-size: 24px;
    font-weight: 900;
    text-transform: uppercase;
}
nav{
    display: flex;
    align-items: center;
    margin: 0 15px;

}
nav a{
    font-size: 20px;
    display: block;
    margin: 0 15px;
    color: brown;
}
</style>