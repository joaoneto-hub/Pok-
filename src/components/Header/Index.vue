<script>

export default {
  name: "Header",

};
</script>

<template>
  <header>
    <img src="../../assets/images/pokemon.webp" alt="Pokemon" />
  </header>
</template>

<style scoped>
header{
  width: 100%;
  height: 6rem;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0px 6px 5px 0px rgba(0,0,0,0.22);
}
img{
  width: 12rem;
}
</style>