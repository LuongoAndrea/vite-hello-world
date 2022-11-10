<template>
  <AppTitle />
</template>

<script>
import AppTitle from './components/AppTitle.vue'
export default {
  components:{
    AppTitle
  },
  data() {
    return {
      message: 'hello word'
    }
  }
}
</script>

<style lang="css">
h1 {
  color: red;
}
</style>

