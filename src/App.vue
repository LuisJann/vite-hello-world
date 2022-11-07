<script>
import AppTitle from "./components/AppTitle.vue";
import AppBanner from "./components/AppHero.vue";

export default {
  data(){
    return{

    }
  },
  components:{
    AppTitle,
    AppHero,
  }
}
</script>

<template>
  <section>
    <AppTitle />
    <AppHero />
  </section>
</template>

<style>

</style>