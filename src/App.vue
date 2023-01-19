<script>
import AppTitle from './components/AppTitle.vue';
export default {
  data() {
    return {
      name: "TestApp",
    }
  },
  components: {
    AppTitle: AppTitle
  }
}
</script>
<template>
  <AppTitle />
</template>
<style>

</style>