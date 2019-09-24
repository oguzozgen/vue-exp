<template>
       <b-card
                  title="JWT Auth Demostration Project"
                  img-src="https://picsum.photos/600/300/?image=25"
                  img-alt="Image"
                  img-top
                  tag="article"
                  style="max-width: 20rem;"
                  class="mb-6 text-center display-flex"
                  >
                    <b-card-text>
                    Samet Temizer 
                    Backend JWT flow
                    Backend Authentication & Authorization API
                    </b-card-text>
                    <b-row>
                      <b-col xs="12"><b-button variant="warning"  v-on:click="routeRegister"> Proceed to Register</b-button></b-col>
                    
                      <b-col xs="12"><b-button variant="success"  v-on:click="routeLogin"> Proceed to Login</b-button></b-col>
                 </b-row>
        </b-card>
</template>
<script>
export default {
    name:'homeNoLogin',
    methods:{
          routeRegister(){ 
              this.$router.push('register');
          },
          routeLogin(){
              this.$router.push('login');
          }
    }
}
</script>
<style>

</style>