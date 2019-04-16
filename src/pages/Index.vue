<template>
  <q-page class="flex flex-center" style="height: 100vh; width: 100wh;">
    <vue-word-cloud :words="[['romance', 19], ['horror', 3], ['fantasy', 7], ['adventure', 3]]" />
  </q-page>
</template>

<style>
</style>

<script>
import VueWordCloud from 'vuewordcloud'

export default {
  components: {
    [VueWordCloud.name]: VueWordCloud
  },

  name: 'PageIndex'
}
</script>
