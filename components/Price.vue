<template>
  <b-container id="price">
    <b-row align-h="center" class="text-center" align="center">
      <b-col cols="12" align-h="center" align-v="stretch">
        <div class="prices">
            <div class="price price__1">
                <h3>Regular Pack</h3>
                <h2>3 Days</h2>
                <ul>
                    <li>Pet Shower</li>
                    <li>Fitness Checkup</li>
                    <li>Pet Grooming</li>
                    <li>Hair and Nail Cut</li>
                    <li>Control Hair Falling</li>
                </ul> 
                <h2>$150 per Visit</h2>
                <button class="first-button red-button">Purchase Pack</button>
                </div>

                            <div class="price price__2">
                <h3>Exclusive Pack</h3>
                <h2>10 Days</h2>
                <ul>
                    <li>Pet Shower</li>
                    <li>Fitness Checkup</li>
                    <li>Pet Grooming</li>
                    <li>Hair and Nail Cut</li>
                    <li>Control Hair Falling</li>
                    <li>Brush & Blow Dry</li>
                    <li>Pet Park And Games</li>



                </ul> 
                                <h2>$350 per Visit</h2>
                <button class="first-button red-button">Purchase Pack</button>
                </div>

                            <div class="price price__3">
                <h3>Premium Pack</h3>
                <h2>30 Days</h2>
                <ul>
                    <li>Pet Shower</li>
                    <li>Fitness Checkup</li>
                    <li>Pet Grooming</li>
                    <li>Hair and Nail Cut</li>
                    <li>Control Hair Falling</li>
                </ul> 
                                <h2>$550 per Visit</h2>
                <button class="first-button red-button">Purchase Pack</button>
                </div>

        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<style lang="scss">
    .prices {
        margin-top: 10rem;
    }
    .price {
        float: left;
        padding: 5rem;
        box-shadow: 5px 5px 2rem gray;

    
    &__1, &__3 {
        background-color: white;
        border-radius: 2rem;
        z-index: -1;
    }

    &__1:hover, &__3:hover {
        background: linear-gradient(to top, #ffa992, #ff7852);
        z-index: 100;
    }


    &__1 {
        margin-right: -3rem;
    }
    &__3 {
        margin-left: -3rem;
        z-index: -1;
    }

    &__2 {
        background: linear-gradient(to top, #ffa992, #ff7852);
        border-radius: 2rem;
        padding-top: 10rem;
        padding-bottom: 10rem;
        color: white;
        margin-top: -5rem;
        z-index: 10;
    }


    }
    .price ul {
        list-style-type: none;
        font-size: 1.7rem;
        margin: 3rem auto;;
    }

    .price h2 {
        margin-bottom: 3rem;
    }

</style>
