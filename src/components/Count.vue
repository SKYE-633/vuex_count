<template>
  <div>
    <button @click="$store.commit('increment')">+</button>
    <span>{{$store.state.count}}</span>
    <button @click="$store.commit('decrement')">-</button>
  </div>
</template>

<script>
import { mapState } from 'vuex'
export default {
  name: 'Count',
  
  data () {
    return {
    
    }
  },
  methods:{
    
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
