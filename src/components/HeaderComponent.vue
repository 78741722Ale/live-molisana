<template>
    <header>
        <!-- Header -->
        <!-- Chiocciola fa sempre riferimento alla cartella SRC -->
        <img alt="Vue logo" src="@/assets/img/la-molisana-logo.png">
        <!-- Navbar -->
        <nav>
            <a href="#">Home</a>
            <a href="#" class="active">Prodotti</a>
            <a href="#">Chi Siamo</a>
            <a href="#">Contatti</a>
        </nav>
    </header>
</template>


<!-- Foglio di Stile per l'header -->
<style lang="scss" scoped>
    
    // Allineo l'header al centro
    header {
        text-align: center;
    }
    
    
    // Annidamento generale, i link (a) dentro la Nav sono senza text decoration
    nav {
        margin: 2rem 0;
        a {
            padding: 0.5rem 1rem;
            text-decoration: none;
            font-size: 0.9rem;
            color: #333;
            font-weight: 600;
            // & equivale al This di JS
            &.active {
                background-color: rgb(209, 233, 242);
            }
            &:hover {
                background-color: rgb(209, 233, 242);
            }
        }
    }



</style>