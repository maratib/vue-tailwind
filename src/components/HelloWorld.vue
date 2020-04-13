<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div
      class="bg-purple-800 text-white sm:bg-green md:bg-blue md:text-yellow lg:bg-red xl:bg-orange"
    >Test</div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
