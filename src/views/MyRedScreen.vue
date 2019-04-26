<template>
  <div class="myRedScreen">
    <h1>This is my red page</h1>
    <MyFragment/>
  </div>
</template>

<script>
import MyFragment from '@/fragments/MyFragment/MyFragment.fragment.vue'
const MyRedScreen = {
  data: function () {
    return {
      greeting: 'hello'
    }
  },
  components: {
    MyFragment
  }
}

export default MyRedScreen
</script>

<style scoped>
.myRedScreen {
    color:red;
}
</style>
