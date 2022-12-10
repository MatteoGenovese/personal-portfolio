<template>
  <div class="container" id="MyProjects">
    <div class="row">
      <SingleCard />
      <SingleCard />
      <SingleCard />
      <SingleCard />
    </div>
  </div>
</template>

<script>

import SingleCard from '@/components/SingleCard.vue'

export default {
  name: 'CardList',
  components: {
    SingleCard
  }
}
</script>

<style lang="scss">


</style>