<template>
  <div class="text-xs-center">
    <v-pagination v-bind:length.number="6" v-model="page" total-visible="3"></v-pagination>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        page: 1
      }
    }
  }
</script>