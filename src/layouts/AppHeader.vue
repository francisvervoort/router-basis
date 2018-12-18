<template>
    <nav class="app-header">
        <h1>
            Beau-tique
        </h1>
        <div class="nav-groep">
        <router-link to="/" exact>Home</router-link>
        <router-link to="/producten">Producten</router-link>
        <router-link to="/over">Over</router-link>
        <router-link to="/contact">Contacteren</router-link>
        </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style>
.app-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #408782;
    height: 6rem;
    padding: 0 2rem;
    color: #fff;
}

.nav-groep a {
    margin: 0 1.5rem;
    text-transform: uppercase;
    font-weight: bold;
    color: #8fdb8f;
    transition: color 0.3s;/*kan op meerdere zaken*/
}

.nav-groep a:hover {
    color: #fff;
}

.nav-groep a.router-link-active{
    color: #FFF;
}
</style>
