<template>
  <div class="home">
    <h1 class="title">项目1-首页3</h1>
    <hello-world></hello-world>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from 'HelloWorld'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  mounted () {
    console.log('Home')
  }
}
</script>
