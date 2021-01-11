<template>
  <div>
    <h1>component</h1>
    <p>{{ msg }}</p>
    <p>{{ name }}</p>
    <p>original message:{{ message }}</p>
    <p>reversed message{{reg}}</p>
  </div>
</template>

<script>
  export default{
    name:'Helloworld',
props:{
  msg:String

},
data(){
  return{
    name:"Rissi Harhan",
    message:"HelloPeople"
  }
},
methods:{
reg:function(){
  return this.message.split('').reverse().join('')
}
}

}
</script>





<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
