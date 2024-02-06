<template>
<div class="background">
  <Logo class = "logo"/>

  <div class="main-info">
    <div>
      <p class="text-white"> Search here</p>
      <!--Search component!-->
    </div>
    <div>
      <img class="w-96" src = "https://www.uber-assets.com/image/upload/f_auto,q_auto:eco,c_fill,w_1144,h_1430/v1684852612/assets/ba/4947c1-b862-400e-9f00-668f4926a4a2/original/Ride-with-Uber.png">
    </div>
  </div>


</div>
</template>

<script>
import Logo from '../components/Logo.vue'

export default {
  components: { Logo },
  name: 'HomeView',
}
</script>

<style scoped>



.background{
  height: 100vh;
}

.main-info{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  align-items: center;
  height: 100%;
}

.logo
{
  position: absolute;
}

</style>
