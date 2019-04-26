<template>
  <div class="home">
    <p>This is my Home</p>
    <MyFragment/>
  </div>
</template>

<script>
import MyFragment from '@/fragments/MyFragment/MyFragment.fragment.vue'

export default {
  name: 'home',
  components: {
    MyFragment
  }
}
</script>
