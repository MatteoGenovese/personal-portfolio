<template>
    <div class="blank">
        <div class="w-100 h-100 d-flex justify-content-center align-content-center align-items-center">
            <img :src="require(`../assets/comingsoon.png`)" alt="" class="profile-photo-clip">
        </div>
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

.blank{
    height: 100vh;
}

</style>