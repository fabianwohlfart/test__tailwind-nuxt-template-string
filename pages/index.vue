<template>
  <div class="container">
    <div
      v-for="item in array"
      :class="`ml-${ item }`"
      >
      Test
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      array: [1, 2, 3, 4, 5]
    }
  }
}
</script>
