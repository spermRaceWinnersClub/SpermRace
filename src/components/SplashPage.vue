<template>
  <div class="splash-wrapper">
    <div class="splash">
      <img
        class="title"
        src="title.jpg"
        alt="Sperm Race Winners Club"
      />
      <img
        class="spermy"
        src="sperm1.gif"
        alt="Spermy, the animated sperm with charming eyes"
      />
      <img
        class="coming-soon"
        src="Comingsoon.jpg"
        alt="Coming Soon"
      />
      <img
        class="social"
        src="twitter.jpg"
        alt="Twitter Channel for Sperm Race Winners Club"
      />
      <img
        class="social"
        src="discord.jpg"
        alt="Discord Channel for Sperm Race Winners Club"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'SplashPage',
  created () {
      document.title = 'Sperm Race Winners Club'
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.splash-wrapper {
    position: relative;
    width: 100vw;
    height: 100%;

    .splash {
        position: absolute;
        width: 100vw;
        height: 100%;
        background-color: #f1b0cf;

        .title {
            display: block;
            margin: auto;
            width: 75%;
            max-width: 900px;
            min-width: 300px;
            height: auto;
        }
        .spermy {
            display: block;
            margin: auto;
            width: 25%;
            max-width: 300px;
            min-width: 160px;
            height: auto;
        }
        .coming-soon {
            display: block;
            margin: auto;
            width: 70%;
            max-width: 840px;
            min-width: 270px;
            height: auto;
        }
        .social {
            margin-top: 4vh;
            width: 12%;
            max-width: 140px;
            min-width: 40px;
            height: auto;

            + .social {
                margin-left: 6%;
            }
        }
    }
}
/*
@media (max-width: 520px) {
    .splash-wrapper {
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        align-content: center;
    }
    .splash {
        display: block;
        top: 50%;
        transform: translateY(-50%);
    }
}
*/
</style>
