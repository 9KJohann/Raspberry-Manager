<script>

import NavItem from "./NavItem.svelte";

</script>
<style>
#nav {
    grid-area: nav;
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


.box {
    background-color: #474747;
    padding: 1rem;
    font-size: 150%;
    color: white;
}
</style>
<nav id="nav" class="box">
    <p>Navleiste jaja</p>
    <ul>
        <NavItem name="Home" path="/" />
        <NavItem name="Spaß" path="/spaß" />
        <NavItem name="Kuhle Seite" path="/kuhleSeite" />
    </ul>
</nav>