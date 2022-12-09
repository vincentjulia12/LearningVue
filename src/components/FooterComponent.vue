<template>
<body class="d-flex flex-column min-vh-100">
    <footer class="mt-auto footer bg-dark text-center text-white">
        <div class="container p-4 pb-0">
            <section class="mb-4">
                <a class="btn btn-outline-light btn-floating m-1" href="https://www.facebook.com/vincentjulia12/" role="button">
                    <i class="fab fa-facebook-f"></i>
                </a>

                <a class="btn btn-outline-light btn-floating m-1" href="https://twitter.com/vj_juliaa" role="button">
                    <i class="fab fa-twitter"></i>
                </a>

                <a class="btn btn-outline-light btn-floating m-1" href="https://www.instagram.com/vj_juliaa/" role="button">
                    <i class="fab fa-instagram"></i>
                </a>

                <a class="btn btn-outline-light btn-floating m-1" href="https://github.com/vincentjulia12" role="button">
                    <i class="fab fa-github"></i>
                </a>
            </section>
        </div>
        <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
            © 2020 Copyright:
            <a id="name" href="https://github.com/vincentjulia12" class="text-white">vincentjulia.com</a>
        </div>
    </footer> 
</body>

</template>

<script>
export default {
    name: "FooterComponent",

    data() {
        return {
            items: {

            }
        }
    }
}
</script>

<style>

</style>