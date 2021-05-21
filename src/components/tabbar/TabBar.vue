<!--  -->

<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'TabBar',
  data () {
    return {
    };
  },
  components: {},
  computed: {},
  mounted(){},
  methods: {}
}
</script>

<style scoped>
  #tab-bar{
    display: flex;
    background: #f6f6f6;
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    box-shadow: 0 -1px 1px rgba(34, 20, 20, 0.1);
  }
</style>