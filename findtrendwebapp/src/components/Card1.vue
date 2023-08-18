<script setup>
// import ButtonComponent from './ButtonComponent.vue';
import TheNavbar from './TheNavbar.vue';
</script>

<template> 
    <div class="Card1">
        <div>
        <TheNavbar/>
        </div>
        <div class= "heroes">
            <div>
            <p>Minimize your tabs.</p>
            <p>Find the trends!</p>
            <p>Don’t let your computer memories consumes all of those browser tabs. 
                Findtrend  let you gathers all of your favorite website into one place.
            </p>
            </div>
            <div class="Start">
            <ButtonComponent class="getstarted" buttonText= "Get started"/>
            </div>
            <img src="@/components/images/img-hero.svg" alt="" class="imgstack">
            <div class="turningTexts">
                <img src="@/components/images/btn-hero-socmed.png" alt="" class="imageUndertext">
            </div>
        </div>
    </div>
</template>

<style scoped>
     .Card1{
      background-color: black;
     }

  .heroes{
    display: flex;
    flex-direction: column;
    justify-content: center;
  }


 .imageUndertext{
    display: flex;
    justify-content: center;
    width: 100%;
    max-width:1440px;
 }