<template>
<div id="principal">
 <v-sheet elevation="6">
  <template>
    <div class="hidden">
      <vs-sidebar
        absolute
        v-model="active"
        open
        >
        <template #logo>
          <!-- ...img logo -->
        </template>
        <vs-sidebar-item id="home">
          <template #icon>
            <i class='bx bx-home'></i>
          </template>
          Home
        </vs-sidebar-item>
        <vs-sidebar-item id="market">
          <template #icon>
            <i class='bx bx-grid-alt'></i>
          </template>
          Market Overview
        </vs-sidebar-item>
        <vs-sidebar-item id="Music">
          <template #icon>
            <i class='bx bxs-music'></i>
          </template>
          Music
        </vs-sidebar-item>
        <vs-sidebar-item id="donate">
          <template #icon>
            <i class='bx bxs-donate-heart' ></i>
          </template>
          Donate
        </vs-sidebar-item>
        <vs-sidebar-item id="drink">
          <template #icon>
            <i class='bx bx-drink'></i>
          </template>
          Drink
        </vs-sidebar-item>
        <vs-sidebar-item id="shopping">
          <template #icon>
            <i class='bx bxs-shopping-bags'></i>
          </template>
          Shopping
        </vs-sidebar-item>
        <vs-sidebar-item id="chat">
          <template #icon>
            <i class='bx bx-chat' ></i>
          </template>
          Chat
        </vs-sidebar-item>
        <template #footer>
          <vs-row justify="space-between">
            <vs-avatar>
              <img src="/avatars/avatar-5.png" alt="">
            </vs-avatar>

            <vs-avatar badge-color="danger" badge-position="top-right">
              <i class='bx bx-bell' ></i>

              <template #badge>
                28
              </template>
            </vs-avatar>
          </vs-row>
        </template>
      </vs-sidebar>
    </div>
  </template>
    <!--   
 <v-img
      src="../assets/Ilustraciones/03.png"
      max-width="600"
     >
 </v-img>
      <div class="icon">
         <v-img
      src="../assets/Ilustraciones/02.png"
     max-width="800"
  >
           </v-img>
           -->
 
 
 <v-main>
      <transition name="bounce">
        <router-view> 
        </router-view>
      </transition>
    </v-main>

 </div>
  
  

</template>

<script>
export default {
  name: 'Entrada', 
  components: {
    
  },
  data: () => {
  
    return {
          
    
    };
  }
};
</script>

<style>
#principal {
 /* background: url('../assets/Background/fondo_inicio2.png') no-repeat center center fixed !important;
  */
 /* background: url('../assets/Ilustraciones/02.png') no-repeat center center fixed !important;
 */ background-size: 25px 50px;
  
}
.title {
color:  white;
text-align: right;
position: relative;
  bottom: -200px;
   right: 200px;
}
.subtitle {
  color:  white;
text-align: right;
position: relative;
  bottom: -220px;
   right: 170px;
   font-size: 35px;
  
}
body{
  margin: 0; 
  padding: 0;
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
.icon {
    align-content: right;
    align-items: right;
    padding-left: 50%;
    position: relative;
  bottom: 450px;
   right: -60px;
   font-size: 50px;
    
}
</style>