<template>

    <nav>
        <router-link to="/" id="logo-url"> 
            <img :src="logo" :alt="alt" id="logo">
        </router-link>
        <router-link to="/">Home</router-link> 
        <router-link to="/pedidos">Pedidos</router-link>
    </nav>

</template>

<script>

export default {
    name: 'NavbarComp',
    props: ["logo", "alt"]
}

</script>

<style scoped>

img {
    max-width: 70px;
    border-radius: 50px;
    border: 1.5px solid #FFD60A;
}

nav {
    background-color: #003566;
    border-bottom: 4px solid #FFD60A;
    padding: 12px 50px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

nav a {
    color: #FFD60A;
    font-size: 28px;
    font-weight: bold;
    text-decoration: none;
    margin: 20px;
    transition: 0.5s;
}

nav a:hover {
    color: blueviolet;
}

#logo-url {
    margin: auto;
    margin-left: 0;
}

</style>
