<template>
  <div class="home">
    <div id="second">
      <router-view></router-view>
      <router-view></router-view>

    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style scoped>

.home{
  display: flex;
  position: relative;
  background-color: green;
  width: 100vw;
  height: 200vh;
  align-items: center;
  justify-content: center;
}

#second{
  position: absolute;
  background-color: red;
  width: 60vw;
  height: 60vh
}

</style>
