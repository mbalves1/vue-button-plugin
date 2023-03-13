<script>
import Vue from 'vue';
import VueButtonTest from '@/vue-button-test.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueButtonTest
  }
});
</script>

<template>
  <div id="app">
    <vue-button-test />
  </div>
</template>
