<template>
    <b-navbar id="nav-bar-custom" toggleable type="dark" variant="primary" >
        <div class="container">
            <b-navbar-brand href="#">Matteo Genovese</b-navbar-brand>
        
            <b-navbar-toggle target="navbar-toggle-collapse">
                <template #default="{ expanded }">
                <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
                <b-icon v-else icon="chevron-bar-down"></b-icon>
                </template>
            </b-navbar-toggle>
        
            <b-collapse id="navbar-toggle-collapse" is-nav>
                <b-navbar-nav class="ml-auto">
                <b-nav-item href="#">Link 1</b-nav-item>
                <b-nav-item href="#">Link 2</b-nav-item>
                </b-navbar-nav>
            </b-collapse>
        </div>
    </b-navbar>
</template>

<script>
export default {

}
</script>

<style lang="scss">


$primary-color-blue: #457B9D ;


nav{
    background-color: var($primary-color-blue) !important;
}



</style>