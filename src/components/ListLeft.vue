<template>
<div>
 <ul>
    <input type="radio" id="list" v-model="list"   @click="list1 = !list1, list = !list">
    <label for="list">List 1 <span></span></label>

    <input type="checkbox" id="item-1" v-model="list1"> <li>Item 1</li>
    <input type="checkbox" v-model="list1"> <li>Item 2</li>
    <input type="checkbox" v-model="list1"> <li>Item 3</li>
    <input type="checkbox" v-model="list1"> <li>Item 4</li>
  </ul>
  <ul>
    <input type="radio" id="list-2" v-model="list2"  @click.stop="list2 = !list2">
    <label for="list-2">List 2 <span></span></label>

    <input type="checkbox" id="item-2"> <li>Item 1</li>
    <input type="checkbox"> <li>Item 2</li>
    <input type="checkbox"> <li>Item 3</li>
    <input type="checkbox"> <li>Item 4</li>
  </ul>
  <ul>
    <input type="radio" id="list-3">
    <label for="list-3">List 3 <span></span></label>

    <input type="checkbox" id="item-3"> <li>Item 1</li>
    <input type="checkbox"> <li>Item 2</li>
    <input type="checkbox"> <li>Item 3</li>
    <input type="checkbox"> <li>Item 4</li>
  </ul>
  <ul>
    <input type="radio" id="list-4">
    <label for="list-4">List 4 <span></span></label>

    <input type="checkbox" id="item-4"> <li>Item 1</li>
    <input type="checkbox"> <li>Item 2</li>
    <input type="checkbox"> <li>Item 3</li>
    <input type="checkbox"> <li>Item 4</li>
  </ul>
</div>
</template>

<script>
export default {
  data() {
    return {
      list: false,
      list1: false,
      list2: false,
      list3: false,
      list4: false,
    };
  },
  methods: {
  },
};
</script>

<style lang="scss">
@import "@/assets/styles/main.scss";
</style>

// Кинуть Пропсы в райт коипонент
