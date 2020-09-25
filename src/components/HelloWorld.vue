<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <Photo />
  </div>
</template>
<script>
import Photo from './Photo'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
components: {
  Photo,
}
}
</script>
<style>
</style>