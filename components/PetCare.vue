<template>
  <b-container class="team-container" id="care">
    <b-row align-h="center">
      <b-col cols="12" md="6"  align-h="center" align-v="stretch">
        <div class="first-container">
          <h2>Professional Pet Care</h2>
          <p>
            Pet owners trust us to look after the needs of their beloved companions. We are specialists committed to delivering the very highest of veterinary care and affection.
          </p>
          <div>
            <button class="first-button red-button">Contact Us Now</button>
          </div>
        </div>
      </b-col>
      <b-col cols="12" md="6"
        ><img class="dog_picture move-picture2" src="~assets/img/dog3.png" alt="Dog"
      /></b-col>
    </b-row>
  </b-container>
</template>

<style lang="scss">

.first-container {
  height: 100%;
  display: flex;
  flex-direction: column;
  //align-items: space-between;
  justify-content: center;
}
.dog_picture {
  width: 100%;
  height: 100%;
}
.first-button {
  color: white;
  padding: 1rem 2rem;
  cursor: pointer;
  border-radius: 20px;
  border: none;
  font-size: 1.7rem;
  width: 23rem;
  transform: translate(0.2s);
}
.red-button {
    background: linear-gradient(to top, #ffa992, #ff7852);
}
.green-button {
  background: linear-gradient(to top, #c3e48f, #8ec637);
}

.red-button:hover {
    background: linear-gradient( #ffa992, #ff7852);
}
.green-button:hover {
  background: linear-gradient(#c3e48f, #8ec637);
}


</style>


<script>

export default {
    mounted() {
const gsap = this.$gsap
gsap.from(".move-picture2", {
  xPercent: 10,
  ease: "none",
  scrollTrigger: {
    trigger: "#care",
    // start: "top bottom", // the default values
    // end: "bottom top",
    scrub: true
  }, 
});




    }

 
}
</script>