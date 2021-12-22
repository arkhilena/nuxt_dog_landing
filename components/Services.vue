<template>
  <b-container class="what-we-do" id="services">
     <b-row align-h="center" align="center">
         <b-col cols="12">
             <h4>Care For Your Pet</h4> 
             <h2>What We Do</h2>
             </b-col>
     </b-row> 
    <b-row align-h="center">
      <b-col cols="6" md="3" >
          <div class="features">
            <div class="icon-features">
                <img class="icon-features__img" src="~assets/img/union.png" alt="">
                </div>
          <h3>Pet Grooming
              </h3>
          <p>There are many variatio of passage of Lorem for a Ipsum available</p>
          </div>  </b-col>
                <b-col cols="6" md="3">
          <div class="features">
            <div class="icon-features">
                <img class="icon-features__img" src="~assets/img/union-4.png" alt="">
                </div>
          <h3>Veterinary
              </h3>
          <p>There are many variatio of passage of Lorem for a Ipsum available</p>
          </div>  </b-col>
                <b-col cols="6" md="3">
          <div class="features">
            <div class="icon-features">
                <img class="icon-features__img" src="~assets/img/union-2.png" alt="">
                </div>
          <h3>Dog Setting
              </h3>
          <p>There are many variatio of passage of Lorem for a Ipsum available</p>
          </div>  </b-col>
                <b-col cols="6" md="3">
          <div class="features">
            <div class="icon-features">
                <img class="icon-features__img" src="~assets/img/union-3.png" alt="">
                </div>
          <h3>Healthy Meals
              </h3>
          <p>There are many variatio of passage of Lorem for a Ipsum available</p>
          </div>  </b-col>
    </b-row>
  </b-container>
</template>

<style lang="scss">
    .what-we-do {
        background-color: $color-background2;
        border-radius: 2rem;
    }

    .features {
        background-color: #fff;
        border-radius: 2rem;
        padding: 5rem 2rem 2rem 2rem;
        margin-bottom: 2rem;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    // .features h3 {
    //     margin: 2rem 0;

    // }

    .icon-features {
        width: 10rem;
        height: 10rem;
        border-radius: 50%;
        background: linear-gradient(to right, #ffa992, #ff7852);
        margin: 0 auto;
        padding-top: 4rem;
        position: relative;
       // background: chocolate;

       &__img {
           position: absolute;
           left: 50%;
           top: 50%;
           margin-left: -2rem;
           margin-top: -2rem;
           
        // align: center;
        // margin: auto;
       }
    }
    // .icon-features img {
    //     align: center;
    //     margin: auto;
    // }

</style>
