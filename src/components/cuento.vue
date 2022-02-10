<template>


     <v-row no-gutters>
         <v-col align="center">
          <div>}
               <h1 class="title"><span style="font-size: 100px;">Leer el cuento</span> </h1>
               <br>
               <br>
               <br>
               <br>
               <br>
              <iframe src="https://drive.google.com/file/d/1gQf3ZBhHpWS9DKC1sAycgrh28JQjoXUL/preview" width="840" height="680" allow="autoplay"></iframe>
          </div>
         </v-col>
       </v-row>
      
      
    
</template>

<script>
export default {
  name: "cuento",
  data: () => ({
    //
  }),
  beforeDestroy() {
    },
};
</script>
<style>
#app {
  background: url('../assets/Background/1.jpg') no-repeat center center fixed !important;
  background-size: cover;
  
}
.title {
   align-content: right;
    align-items: right;
     padding-top: 90px;
    padding-left: 20%;
    position: relative;
  bottom: -90px;
   right: 300px;
   font-size: 500px;
  width: -100px;
  display: flex;
  justify-content: center;
  /* Fin del codigo para centrar*/
}
.subtitle {
align-content: right;
    align-items: right;
     padding-top: 90px;
    padding-left: 20%;
    position: relative;
  bottom: -90px;
   right: 300px;
   font-size: 50px;
  width: -100px;
  display: flex;
  justify-content: center;
}
body{
  margin: 0; 
  padding: 0;
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
h1 {
  color: black;
}
h3{
  color: black;
}
.icon {
    align-content: right;
    align-items: right;
    padding-left: 55%;
    position: relative;
  bottom: 590px;
   right: -200px;
   font-size: 50px;
    align-content: right;
    align-items: right;
     padding-top: 480px;
    position: relative;
    
}
</style>