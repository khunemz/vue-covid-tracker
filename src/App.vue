<template>
  <Header />
  <div class="container mx-auto px-4">
    <router-view/>
  </div>
</template>


<script>
import Header from '@/components/Header'
export default {
  components: {
    Header,
  }
}
</script>
<style>

</style>
