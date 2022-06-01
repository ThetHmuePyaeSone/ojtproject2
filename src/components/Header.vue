<template>
  <h2 class="header">{{ name }}</h2>
</template>

<script>
export default{
    name:'HeaderComponent',
     data() {
    return {
      name: 'Welcome from OJT Project 2'
    }
  }
}
</script>
<style scoped>
.header{
    background-color: rgb(126, 49, 104);
    color: white;
    height: 76px;
    padding-top: 33px;
}
</style>
