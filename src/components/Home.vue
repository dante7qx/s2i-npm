<template>
  <div id="home">
      <h1>欢迎来到 CaaS 容器云</h1>
      <div v-html="info"></div>
  </div>
  
</template>

<script>
import info from '../assets/info.txt'

export default {
    data() {
        return {
            info
        }
    }
}
</script>
<style scoped>
#home div {
    text-align: center;
}
</style>