<template>
    <nav class="navbar navbar-dark bg-dark navbar-expand-sm">
        <div id="nav-container" class="container d-flex justify-content-center align-items-center">
            <div>
                <router-link class="navbar-brand" to="/"><span id="first-name">Vincent</span></router-link> 
            </div>
           
            <div id="nav-right-section" class="d-flex justify-content-end collapse navbar-collapse">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <router-link class="nav-link px-3" to="/"><span id="hover">Home</span></router-link>
                    </li>
                </ul>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <router-link class="nav-link px-3" to="/users"><span id="hover">Users</span></router-link>
                    </li>
                </ul>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <router-link class="nav-link px-3" to="/about"><span id="hover">About</span></router-link>
                    </li>
                </ul>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <router-link class="nav-link px-3" to="/faq"><span id="hover">Faq's</span></router-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style>

</style>