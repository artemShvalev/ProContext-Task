<template>
  <div id="app">
    <ListLeft/>
    <ListRight/>
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
};
</script>
