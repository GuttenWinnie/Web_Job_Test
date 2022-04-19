<template>
  <div>
    <FormControl />
    <Comments />
    </div>
</template>

<script>
import Comments from '@/components/Comments'
import FormControl from '@/components/FormControl'
export default {
  name: 'App',
  components: {
    Comments,
    FormControl
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
