<template>
    <div>

        <HomeJumbotron />
        <CoreTechnologies />

    </div>
</template>

<script>

import HomeJumbotron from '@/components/HomeJumbotron.vue'
import CoreTechnologies from '@/components/CoreTechnologies.vue'

export default {
  name: 'HomePortfolio',
  components: {
    HomeJumbotron,
    CoreTechnologies
  }
}
</script>

<style>

.box{

    height: 900px;
    width: 100%;
    justify-content:flex-start;
}

.profile-photo{
    clip-path: polygon(25% 0%, 100% 0%, 75% 100%, 0% 100%);
}

</style>