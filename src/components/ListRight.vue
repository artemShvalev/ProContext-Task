/* eslint-disable max-len */
<template>
  <div>
    <div class="all__list">
      <strong
      :class="{hiddenElem: !elem1, showElem: elem1}"
      @click="elem1 = !elem1"> List1
      </strong>
      <div class="list1__result"  v-show="elem1">
        <span ></span>
        <span></span>
        <span></span>
        <span></span>
        <button>Перемешать</button>
      </div>
      <strong @click="elem = !elem"
      :class="{hidden: !elem, show: elem}"
      > List2
      </strong>
      <div class="list1__result" v-show="elem">
        <button>Перемешать</button>
      </div>
      <strong
      :class="{hiddenElem: !elem2, showElem: elem2}"
      @click="elem2 = !elem2"
      > List3 </strong>
      <div class="list1__result" v-show="elem2">
        <button>Перемешать</button>
      </div>
      <strong
      :class="{hiddenElem: !elem3, showElem: elem3}"
      @click="elem3 = !elem3">
       List4
       </strong>
      <div class="list1__result" v-show="elem3">
        <button>Перемешать</button>
      </div>
  </div>

  </div>
</template>

<script>

export default {
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
  data() {
    return {
      elem: true,
      elem1: true,
      elem2: true,
      elem3: true,
    };
  },
};
</script>

<style>

</style>
