<template>
  <div>
    <h2>Hello Compositon API</h2>
  </div>
  <TestComponent />
</template>
<script>
import TestComponent from "./components/composition/TestComponent";
export default {
  name: "App",
  components: {
    TestComponent,
  },
  data() {
    return {};
  },
  computed: {},
  watch: {},
  ditrectives: {},
  methods: {},
};
</script>
<style></style>
