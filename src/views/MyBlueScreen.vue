<template>
  <div class="myBlueScreen">
    <h1>This is my blue page</h1>
    <MyFragment/>
  </div>
</template>

<script>
import MyFragment from '@/fragments/MyFragment/MyFragment.fragment.vue'
const MyBlueScreen = {
  data: function () {
    return {
      greeting: 'hello'
    }
  },
  components: {
    MyFragment
  }
}

export default MyBlueScreen
</script>

<style scoped>
.myBlueScreen {
    color:blue;
}
</style>
