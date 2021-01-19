<template>
  <h1>{{ title }}</h1>
</template>

<script>
export default {
  name:'title',
  data(){
    return {
      title:'Hello Rick!'
    }
  }
}
</script>

<style>
  h1{
    color:yellow;
  }
</style>