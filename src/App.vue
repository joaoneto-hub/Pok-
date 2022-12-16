<script>
import Header from "./components/Header/Index.vue";
import Card from "./components/Card/index.vue";
export default {
  name: 'App',
  components:{
    Header,
    Card
  },

  data: () => ({
    //
  }),
}
</script>

<template>
  <div>
    <Header />
    <Card />
  </div>
</template>


