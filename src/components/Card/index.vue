<script></script>

<template>
  <div>
    <div class="Card">
      <div class="id-poke">
        <h3>#001</h3>
      </div>
      <img src="../../assets/images/Poke.png" alt="" />
  
      <div class="Card-name-Poke">
        <h2 class="Name-poke">Squirtle</h2>
      </div>
    </div>
    <div class="Card">
      <div class="id-poke">
        <h3>#001</h3>
      </div>
      <img src="../../assets/images/Poke.png" alt="" />
  
      <div class="Card-name-Poke">
        <h2 class="Name-poke">Squirtle</h2>
      </div>
    </div>
    <div class="Card">
      <div class="id-poke">
        <h3>#001</h3>
      </div>
      <img src="../../assets/images/Poke.png" alt="" />
  
      <div class="Card-name-Poke">
        <h2 class="Name-poke">Squirtle</h2>
      </div>
    </div>
  </div>
</template>

<style scoped>
div{
  display: flex;
}
.Card {
  width: 13rem;
  height: 13rem;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  border: 2px solid #74cb48;
  border-radius: 8px;
}
.id-poke{
  color: #74cb48;
  margin-left: 8rem;
}
.Card-name-Poke{
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #74cb48;
}
.Name-poke{
  color: #fff;
  font-weight: 50;
}
img{
  width: 10rem;
}
</style>
