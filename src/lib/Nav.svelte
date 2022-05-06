<script>

import NavItem from "./NavItem.svelte";

</script>
<style>
#nav {
    grid-area: nav;
    background-color: #2f3837;
}
   

nav ul {
    list-style-type: none
}



#nav {
    padding: 0;
}

nav p {
    padding: 1rem;
}
</style>
<nav id="nav">
    <p>Navleiste jaja</p>
    <ul>
        <NavItem name="Home" path="/" icon="home" />
        <NavItem name="Netzwerk" path="/network" icon="lan" />
    </ul>
</nav>