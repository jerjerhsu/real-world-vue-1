<template>
  <div id="product">
    <h1>
        {{ testmsg }}
    </h1>
    <ul>
      <li></li>
      <li></li>
      <li></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "TestComponent",
  props: {
    testmsg: String
  }
};
</script>


<style lang="sass" scoped>
    #product
        color: #f00
        text-decoration: underline
</style>
<style lang="scss" scoped>
    #product{
        h1{
            font-size: 35px;
        }
    }
</style>

