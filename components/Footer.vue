<template>
  <b-container id="footer">
    <b-row align-h="center">
      <b-col cols="6" md="5" align-h="center" align-v="stretch">
          <h2>Vetcare</h2>
          <p>Quisque id leo non dolor tempor elementum quis ac urna. Nam pharetra, ligula eget finibus dignissim, turpis ipsum sollicitudin</p>
          
                  <!-- <b-form inline @submit="onSubmit" @reset="onReset" v-if="show">
      <b-form-group id="input-group-1" label="Email address:"  label-for="input-1" description="We'll never share your email with anyone else.">
        <b-form-input id="input-1" v-model="form.email" type="email" placeholder="Enter email" required></b-form-input>
      </b-form-group>
      <b-button type="submit" variant="primary">Submit</b-button>
          </b-form> -->
      </b-col>
      <b-col cols="6" md="2">
          <h3>Address</h3>
          <ul><li>
              +23 384 485 29
          </li>
          <li>vet@shamim.com</li>
          <li>
          123 king street, Melbrown
Victoria 3000, Australia
</li>
</ul>
        </b-col>
        <b-col cols="6" md="2">
             <h3>Links</h3>
          <ul><li>
              About Us
          </li>
          <li>Contact Us</li>
          <li>
          Groomers
</li>
<li>Privacy Policy</li>
<li>Tearms</li>
</ul>   
        </b-col>
        <b-col cols="6" md="3">
            
                         <h3>Opening Hours</h3>
          <ul><li>
              Monday-Tuesday 09:00-18:00
          </li>
          <li>Wednesday 09:00-18:00</li>
          <li>
         Thrusday-Friday 09:00-18:00
</li>
<li>Saturday 10:00-17:00</li>
<li>Sunday 10:30-16:00</li>
</ul>  
            
            </b-col>

    </b-row>
     <b-row align-h="center">
      <b-col cols="12" class="text-center">
          <p>© Copyright 2022 | Pet Theme by Arkhilena | All Rights Reserved</p>
      </b-col>
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

#footer li {
    font-size: 1.5rem;
    list-style: none;
    

}



</style>


<script>
  export default {
    data() {
      return {
        form: {
          email: '',
        },
      }
    },
    methods: {
      onSubmit(event) {
        event.preventDefault()
        alert(JSON.stringify(this.form))
      },
      onReset(event) {
        event.preventDefault()
        // Reset our form values
        this.form.email = ''
        // Trick to reset/clear native browser form validation state
        this.show = false
        this.$nextTick(() => {
          this.show = true
        })
      }
    }
  }
</script>
