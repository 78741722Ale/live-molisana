<template>
    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="row">
                <!-- Logo di Molisano -->
                <div class="col text_center ">
                    <img src="@/assets/img/la-molisana-logo.png" alt="">
                </div>
                <!-- Prima lista -->
                <div class="col">
                    <!-- Title -->
                    <h3>Pastificio</h3>
                    <!-- List -->
                    <ul>
                        <li>Il Pastificio</li>
                        <li>Grano</li>
                        <li>Filiera</li>
                        <li>100 anni di pasta</li>
                        <li>Storia della pasta</li>
                    </ul>
                </div>
                <!-- Seconda lista -->
                <div class="col">
                    <!-- Title -->
                    <h3>Pastificio</h3>
                    <!-- List -->
                    <ul>
                        <li>Il Pastificio</li>
                        <li>Grano</li>
                        <li>Filiera</li>
                        <li>100 anni di pasta</li>
                        <li>Storia della pasta</li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<!-- Export del footer -->
<script>
export default {
    name: 'FooterComponent'
}
</script>

<!-- Foglio di Stile per il Footer -->
<style lang="scss" scoped>

// site Footer
Footer {
    background-image: url("@/assets/img/footer-montagne-bottom.jpg");
    background-repeat: no-repeat;
    background-position: bottom;
    height: 400px;
    padding-top: 3rem;
    // Titolo H3
    h3 {
        margin: 1.25rem;
    }
    // Lista non ordinata globale
    ul {
        list-style: none;
        line-height: 1.5rem;
    }


}
</style>