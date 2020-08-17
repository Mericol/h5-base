<template>
  <div class="hello">
    <div class="bg-red"></div>    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.bg-red{
  width:1rem;
  height:1rem;
  background: red;
}
</style>
