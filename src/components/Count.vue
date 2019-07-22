<template>
  <div class="hello">
    <button @click="increase">+</button>
    <span>{{count}}</span>
    <button @click="decrease">-</button>
  </div>
</template>

<script>
import { mapState } from 'vuex'
export default {
  name: 'Count',
  props: {
    msg: String
  },
  data () {
    return {
     count: 0
    }
  },
  methods:{
    increase () {
      this.count++
    },
    drease () {
      this.count--
    }
  },
  computed: mapState({
    
  })
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
