<template>
  <div>
    <h1>{{ parent_msg }}</h1>
    <h2>{{ local_data }}</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    parent_msg: String
  },
  data() {
    return {
      local_data : "dana lokalna z HelloWorld.vue"
    }
  }
}
</script>


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
