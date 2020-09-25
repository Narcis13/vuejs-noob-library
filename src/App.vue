<template>
  <div id="app">
   <!-- <Sidebar />  -->
   <Button caption="Uraa"></Button>
  </div>
</template>

<script>
  import Sidebar from './components/Sidebar'
  import Button from './components/Button'
  export default {
    components: {
      Sidebar,
      Button
    }
  };
</script>

<style lang="scss">
  @import url("https://use.fontawesome.com/releases/v5.11.0/css/all.css");
  @import url("https://fonts.googleapis.com/css?family=Play");

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-size: 1rem;
    font-family: "Play", Tahoma;
    background-color: #ccc;
    color: #333;
  }

  #app {
    position: relative;
    padding: 20px;
    min-height: 100vh;
    width: 100%;
  }
</style>
