<template>

<hero/>
  <footers/>
</template>

<script>
import navbar from "@/components/nav";
import hero from "@/components/hero";
import footers from "@/components/footer";
export default {
  name: "Home",
  components:{
    navbar,
    hero,
    footers
  }
}
</script>

<style scoped>

</style>