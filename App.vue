<template>
    <div id="App">
        <ul class="nav" style="background-color:#e3f2fd">
            <li class="nav-item">
                <router-link class="nav-link" to="/">Home</router-link>
            </li>
            <li class="nav-item">
                <router-link class="nav-link" to="/about">About</router-link>
            </li>
            <li class="nav-item">
                <router-link class="nav-link" to="/contact">Contact</router-link>
            </li>
        </ul>

        <router-view></router-view>

    </div>
</template>

<script>
export default {
    name: 'App',
    components: {

    }
}
</script>

<style>
#app {
    font-family: Avenir, Halvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialised;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;


}
</style>