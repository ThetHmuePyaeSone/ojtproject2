<template>
  <div class="secondcontent">
    <h2 class="movie">{{message}}</h2>
    <Header />
    <ul>
      <li v-for="(movie, x) in movies" :key="x" >{{movie.name}}</li>
    </ul>
  </div>
</template>

<script>
export default {
   name:'SecondComponent',
   data(){
       return{
           movies:[
               {name:'Mone Swal'},
               {name:'ME'},
               {name:'Nga Duu'},
               {name:'Mystery Of Burma'},
               {name:'Phone Shate'},
               {name:'Mudras Calling'},
               {name:'Deception'}
           ],
           message:'Welcome from Movies List...',
        } }
}
</script>
<style scoped>
.secondcontent{
    padding: 115px;
    margin-left: 50px;
    margin-right: 50px;
    background-color: rgb(215, 212, 212);
    font-size: 0.7rem;
    }

 ul{
   margin-top: 50px;
 }   
ul li {
  display: table;
  color: black;
  font-size: 3em;
  
}
ul li:before {
  content: "• ";
}
h2{
    font-size: 3.5em;
}
</style>
