<template>
    <div>

        <HomeJumbotron />

        <AboutMe />

        <CoreTechnologies />

        <MyProjects />

    </div>
</template>

<script>

import HomeJumbotron from '@/components/HomeJumbotron.vue'
import CoreTechnologies from '@/components/CoreTechnologies.vue'
import AboutMe from '@/components/AboutMe.vue'
import CardList from '@/components/CardList.vue'
import MyProjects from '@/components/MyProjects.vue'

export default {
  name: 'HomePortfolio',
  components: {
    HomeJumbotron,
    CoreTechnologies,
    AboutMe,
    CardList,
    MyProjects
  }
}
</script>

<style lang="scss">

.profile-photo{
    clip-path: polygon(25% 0%, 100% 0%, 75% 100%, 0% 100%);
}

</style>