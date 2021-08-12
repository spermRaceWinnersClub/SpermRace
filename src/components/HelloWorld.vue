<template>
  <div class="splash">
      <img
        class="title"
        src="title.jpg"
        alt="Sperm Race Winners Club"
      />
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.splash {
    position: absolute;
    width: 100vw;
    height: 100vh;
    background-color: #f1b0cf;

    .title {
        width: 80%;
        height: auto;
        padding-top: 10vh;
    }
}
</style>
