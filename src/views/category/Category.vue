<!--  -->

<template>
  <div>
    <div>我是About</div>
    <p>{{$store.state.counter}}</p>
    <button @click = 'addition'>增加</button>
    <button @click = 'subtraction'>减少</button>
  </div>
</template>
 
<script>
export default {
  name: 'Category',
  data () {
    return {
    };
  },
  components: {},
  // computed: {
  //   count : function(){
  //     return this.$store.state.counter
  //   }
  // },
  mounted(){},
  methods: {
    addition(){
      this.$store.commit('increment')
    },
    subtraction(){
      this.$store.commit('decrement')
    }
  }
}
</script>

<style scoped>

</style>