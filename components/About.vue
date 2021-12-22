<template>
  <b-container id="about">
    <b-row align-h="center">
      <b-col cols="12" md="6" align-h="center" align-v="stretch">
        <div class="about-container">
            <h4>Our Success Story</h4>
          <h2>Experience Vet Clinic And Services</h2>
          <p>
            Aliquam erat volutpat In id fermentum augue, ut pellentesque  Maecenas at arcu risus. Donec commodo sodales ex, scelerisque laoreet nibh hakso hendrerit id. In aliquet magna nec lobortis maximus.
          </p>
          <ul class="about">
              <li>Donec commodo scelerisque laoreet nibh hendrerit</li>
              <li>In aliquet magna nec lobortis maximus. Etiam a dolor placerat</li>
              <li>Etiam dolor nec elementum ipsum convall Maecenas</li>
          </ul>
          <div>
            <button class="first-button red-button">Know More About Us</button>
            
          </div>
        </div>
      </b-col>
      <b-col cols="12" md="6"
        ><img class="dog_picture move-picture" src="~assets/img/dog2.png" alt="Dog"
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

.about li {
    font-size: 1.7rem;
    list-style-type: none;
    text-indent: .5rem;
    line-height: 3.7rem;

}
.about li::before {
    content: "";
    background: url('../assets/img/Union-6.png');
    float: left;
    width: 2.5rem;
    height: 2.5rem;
}




</style>


<script>

export default {
    mounted() {
const gsap = this.$gsap
gsap.from(".move-picture", {
  xPercent: 10,
  ease: "none",
  scrollTrigger: {
    trigger: "#about",
    // start: "top bottom", // the default values
    // end: "bottom top",
    scrub: true
  }, 
});




    }

 
}
</script>