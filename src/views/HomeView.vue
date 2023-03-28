<template>
  <div class="home">
    <navbar/>
    <bodyComponent/>
    <foot/>


    
  </div>  
</template>

<script>
// @ is an alias to /src
import navbar from '../components/navbar.vue'
import foot from '../components/foot.vue'
import bodyComponent from '@/components/bodyComponent.vue';

export default {
  name: 'HomeView',
  components: {
    navbar,
    foot,
    bodyComponent
}
}
</script>
