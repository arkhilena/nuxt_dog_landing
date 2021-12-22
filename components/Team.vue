<template>
  <b-container class="team-container" id="team">
     <b-row align-h="center" align="center">
         <b-col cols="12">
             <h4>Our Team</h4> 
             <h2>Meet Our Groomers</h2>
             </b-col>
     </b-row> 
    <b-row align-h="center">
      <b-col cols="6" md="3">
          <div class="team">
            <div class="icon-team">
                <img class="icon-team__img" src="~assets/img/vet1.png" alt="">
                </div>
          <h3>Rosalina Wiliam
              </h3>
          <p>CEO & Founder</p>
          </div>  </b-col>
                <b-col cols="6" md="3">
          
            <div class="team">
            <div class="icon-team">
                <img class="icon-team__img" src="~assets/img/vet2.png" alt="">
                </div>
          <h3>Rosalina Wiliam
              </h3>
          <p>CEO & Founder</p>
          </div>  </b-col>
                <b-col cols="6" md="3">
          <div class="team">
            <div class="icon-team">
                <img class="icon-team__img" src="~assets/img/vet3.png" alt="">
                </div>
         <h3>Rosalina Wiliam
              </h3>
          <p>CEO & Founder</p>
          </div>  </b-col>
                <b-col cols="6" md="3">
          <div class="team">
            <div class="icon-team">
                <img class="icon-team__img" src="~assets/img/vet4.png" alt="">
                </div>
          <h3>Rosalina Wiliam
              </h3>
          <p>CEO & Founder</p>
          </div>  </b-col>
    </b-row>
  </b-container>
</template>

<style lang="scss">
    .team-container {
        background-color: $color-background2;
        border-radius: 2rem;
    }

    .team {
        background-color: #fff;
        border-radius: 15rem;
        padding: 5rem 2rem 2rem 2rem;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    // .fteam h3 {
    //     margin: 2rem 0;
    // }

    .icon-team {
        width: 20rem;
        height: 20rem;
        border-radius: 50%;
        background: linear-gradient(#C3E48F, #8EC637
);
        margin: 0 auto;
        padding-top: 4rem;
        position: relative;
       // background: chocolate;

       &__img {
           position: absolute;
           top: 50%;
           left:50%;
           width: 20rem;
           height: 20rem;
           margin-left: -10rem;
           margin-top: -10rem;

       }

    }
    // .icon-features img {
    //     align: center;
    //     margin: auto;
    // }

</style>
