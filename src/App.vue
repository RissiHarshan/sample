<template>
  <div class="App">
    <Helloworld msg="hellohi"/>
    
    </div>
</template>

<script>
  import Helloworld from '@/components/HelloWorld.vue'
  export default{
    name:'App',
    components: {
      Helloworld
    },
  }

</script>



<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
