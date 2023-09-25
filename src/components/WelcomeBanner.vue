<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="welcome-banner">
    <div class="titles">
      <div class="neons">
        <h1>Aysia Brown</h1>
        <h2>Software Engineer</h2>
      </div>
      <div class="tagline">
        <h3>Open For Work</h3>
        <p>2 years of professional experience as a full stack developer</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Croissant+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Rock+Salt&display=swap');

.welcome-banner {
  background-color: black;
  background-size: cover;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  height: 700px;
  margin: 0;
  color: #fff;
  box-shadow:  0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    .titles {
      padding-top: 15em;
      padding-left: 5em;
      display: flex;
      justify-content: space-between;

      .neons {
        border: #fff 5px solid;
        border-radius: 25px;
        padding-bottom: 3em;
        width: 30em;
        box-shadow: 0 0 .2rem #fff,
              0 0 .2rem pink,
              0 0 2rem hotpink,
              0 0 0.8rem hotpink,
              0 0 2.8rem hotpink,
              inset 0 0 1.3rem hotpink;

          text-shadow: 
            0 0 10px #fff,
            0 0 21px pink,
            0 0 32px pink,
            0 0 42px hotpink,
            0 0 82px hotpink,
            0 0 92px hotpink,
            0 0 102px hotpink,
            0 0 112px hotpink;
          }

      .tagline {
        margin-right: 5em;

      }

      h1 {
        font-family: 'Dancing Script', cursive;
        font-size: 72px;
        text-transform: lowercase;
        text-align: center;
        animation: pulse 2.5s infinite alternate;
      }

      h2 {
        font-family: 'Croissant One', cursive;
        text-transform: uppercase;
        text-align: center;
        animation: flicker 5s infinite alternate;
      }

      h3 {
        font-family: 'Rock Salt', cursive;
        font-size: 32px;
        margin-bottom: 0px !important;
      }

      p {
        font-family: 'Croissant One', cursive;
        margin-top: 0px !important;
      }
  }
}


@keyframes flicker {
    
    0%, 18%, 22%, 25%, 53%, 57%, 100% {
  
        text-shadow:
        0 0 10px #fff,
        0 0 21px pink,
        0 0 32px pink,
        0 0 42px hotpink,
        0 0 82px hotpink,
        0 0 92px hotpink,
        0 0 102px hotpink,
        0 0 112px hotpink;
    
    }
    
    20%, 24%, 55% {        
        text-shadow: none;
    }    
  }

  @keyframes pulse {
      100% {
    
          text-shadow:
          0 0 10px #fff,
          0 0 21px pink,
          0 0 32px pink,
          0 0 42px hotpink,
          0 0 82px hotpink,
          0 0 92px hotpink,
          0 0 102px hotpink,
          0 0 112px hotpink;
      
      }
      
      0% {        
          text-shadow:           
          0 0 2px #fff,
          0 0 10px pink,
          0 0 16px pink,
          0 0 21px hotpink,
          0 0 41px hotpink,
          0 0 51px hotpink,
          0 0 62px hotpink,
      }    
  }
</style>
