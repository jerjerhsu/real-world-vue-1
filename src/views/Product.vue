<template>
  <div class="product">
    <h1>This is an product page</h1>
    <TestComponent testmsg="This is TestComponent"></TestComponent>
  </div>
</template>

<script>
import TestComponent from "@/components/TestComponent.vue";

// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "product",
  components: {
    TestComponent
  }
}
</script>

<style>

</style>
