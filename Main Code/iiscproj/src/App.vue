<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <router-link to="/" class="navbar-brand">Home</router-link>
            <button
                class="navbar-toggler"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#navbarNavAltMarkup"
                aria-controls="navbarNavAltMarkup"
                aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <router-link to="/model" class="nav-link active"
                        >Model</router-link
                    >
                </div>
            </div>
        </div>
    </nav>
    <router-view />
    <footer>
        <div class="container-fluid">
            <div class="row">
                <div class="col-12 text-center">
                    <p>
                        <small>&copy; 2023 Ooga Booga Inc.</small>
                    </p>
                </div>
            </div>
        </div>
    </footer>
</template>

<style>
    /* light grey background to the entire template*/
    #app {
        background-color: #ffffff;
    }
</style>
