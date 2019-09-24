<template>
         <b-card
                  title="LOGGED IN"
                  tag="article"
                  style="max-width: 40rem;"
                  class="mb-6 text-center display-flex"
                  >
                    <hr />
                    <b-card-text>
                    Samet Temizer 
                    Backend JWT flow
                    Backend Authentication & Authorization API
                    </b-card-text>
                     <b-card-text>
                                <slot></slot>
                    </b-card-text>
                    
                  
        </b-card>
</template>
<script>

export default {
    name:'HomeLoggedInComp',
    data(){
        return{
            data:[]
        }
    },
    components:{

    },
    methods:{
       
    }
}
</script>
<style>

</style>