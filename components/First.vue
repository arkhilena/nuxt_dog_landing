<template>
  <b-container id="start" fluid="md">
    <b-row align-h="center">
      <b-col cols="12" md="6" align-h="center" align-v="stretch">
        <div class="first-container">
          <h1 v-gsap.fromTo="[ { opacity: 0, y: -350 },{ opacity: 1, y: 0, duration: 3 }]">For Your Pet’s Natural Life & Care</h1>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod tempor incididunt
          </p>
          <div>
            <button class="first-button red-button"><a href="#services">Our Services</a></button>
            <button class="first-button green-button"><a href="tel:+78142332211">Make Appointment</a></button>
          </div>
        </div>
      </b-col>
      <b-col cols="12" md="6"
        ><img class="dog_picture" src="~assets/img/dog.png" alt="Dog"
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
  padding: 1rem;
  cursor: pointer;
  border-radius: 20px;
  border: none;
  font-size: 1.7rem;
  width: 17rem;
  transform: translate(0.2s);

  a {
    color: white;
    text-decoration: none;
  }
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
gsap.from(".dog_picture", {
  xPercent: 10,
  ease: "none",
  scrollTrigger: {
    trigger: "#start",
    // start: "top bottom", // the default values
    // end: "bottom top",
    scrub: true
  }, 
});




    }

 
}
</script>