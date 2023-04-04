<script>
    export default {
        name: 'NavBar'
    }
</script>

<template>
  <div id="nav-bar">
   <img id="ironhack-logo" src="../images/Ironhack_logo.png" alt="Ironhack Logo">
   <img id="burger-menu" src="../images/Burger_menu.png" alt="Burger Menu">
  </div>
</template>

<style scoped>
  #nav-bar {
    margin: 25px 35px 30px;
    display: flex;
    justify-content: space-between;
  }
  #ironhack-logo {
    width: 37px;
    height: 40px;
  }
  #burger-menu {
    width: 25px;
    height: 20px;
  }
                                                                                    
</style>