/<template>
  <div>

    <div class="all__list">
    <div class="template__result">
      <strong> List1 </strong>
      <div class="list1__result">
        <button>Перемешать</button>
      </div>
      <strong> List2 </strong>
      <div class="list1__result">
        <button>Перемешать</button>
      </div>
      <strong> List3 </strong>
      <div class="list1__result">
        <button>Перемешать</button>
      </div>
      <strong> List4 </strong>
      <div class="list1__result">
        <button>Перемешать</button>
      </div>
    </div>
  </div>

  </div>
</template>

<script>
export default {
  props: {
    value: Number,
  },
  data() {
    return {
      elem: true,
    };
  },
};
</script>

<style>

</style>
