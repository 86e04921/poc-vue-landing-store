<template>
    <div id="app">
        <div class="hero-head">
            <div class="container">
                <nav class="nav">
                    <div class="container">
                        <div class="nav-left">
                            <router-link to="/" class="nav-item">Pusheen</router-link>
                        </div>
                    </div>
                </nav>
            </div>
        </div>
        <router-view></router-view>
    </div>
</template>

<style scoped>
    #app {
        min-height: 100vh;
        position: relative;
    }
</style>

<script>
    export default {
        name: 'app',
        data() {
            return {}
        }
    }
</script>