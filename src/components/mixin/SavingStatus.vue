<template>
  <div>
    <h2>총적금: {{ totalMoney }}</h2>
    <button @click="addMoney(1000)">1000</button>
    <button @click="addMoney(2000)">2000</button>
    <button @click="addMoney(1150)">1150</button>
    <button @click="addMoney(2200)">2200</button>
  </div>
</template>

<script>
import useMoney from "../../composables/useMoney";
export default {
  name: "SavingStatus",
  setup() {
    const { addMoney, totalMoney } = useMoney(5000);

    return {
      addMoney,
      totalMoney,
    };
  },

  components: {},
  methods: {},
};
</script>

<style></style>
