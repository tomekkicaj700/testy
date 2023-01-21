<template>
  <div>
    <HelloWorld :parent_msg="app_data1"/>
    <HelloWorld parent_msg="app_data1 1"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {

  components: {
    HelloWorld
  },
  data() {
 
     return {

        app_data1 : "app local data value"

     }

  }
}
</script>


