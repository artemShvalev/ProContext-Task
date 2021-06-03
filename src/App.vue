<template>
  <div id="app">
    <ListLeft/>
    <ListRight :propValue="propValue.value" v-bind:propColor="propColor.color" />
  </div>
</template>

<script>
import ListLeft from './components/ListLeft.vue';
import ListRight from './components/ListRight.vue';

export default {
  name: 'App',
  components: {
    ListLeft,
    ListRight,
  },
  props: {
    propValue: {
      value: Number,
      default: 0,
    },
    propColor: {
      color: Object,
      default: false,
    },
  },
};
</script>
