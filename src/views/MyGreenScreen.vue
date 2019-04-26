<template>
  <div class="myGreenScreen">
    <h1>This is my green page</h1>
    <MyFragment/>
  </div>
</template>

<script>
import MyFragment from '@/fragments/MyFragment/MyFragment.fragment.vue'
const MyGreenScreen = {
  data: function (){
    return {
       greeting: 'hello'
    }
  },
  components: {
    MyFragment
  }
}

export default MyGreenScreen
</script>

<style scoped>
.myGreenScreen {
    color:green;
}
</style>
