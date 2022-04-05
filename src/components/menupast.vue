<template>
     <section class="titulo">
            <img src="../assets/logopasterely-chico.png" alt="">
    </section>
    <section class="panes">
        <H2>Sabores de pan</H2>
        <p>Chocolate</p>
        <p>Red velvet</p>
        <p>Vainilla</p>
    </section>
    <section class="rellenos">
        <h2>Rellenos </h2>
        <p>Chocolate turin</p>
        <p>Galletas oreo</p>
        <p>Queso crema</p>
        <p>Dulce de leche</p>
        <p>Crema pastelera con duraznos</p>
        <p>Crema pastelera con fresa</p>
        <p>Cajeta</p>
    </section>
    <section class="decoracion">
        <h2>Decoraciones</h2>
        <p>Chocolates</p>
        <p>butter cream</p>
        <p>Flores</p>
        <p>Cake topper</p>
        <p>Frutas</p>
        <p>Galletas</p>
        <p>Fondant</p>
    </section>
    <section class="precios">
        <h2>Precio Pasteles</h2>
        <h3>Pan de chocolate</h3>
        <p>Pan de chochocolate con relleno y cobertura de chocolate turin o galletas oreo -------- $270</p>
        <p>Pan de chocolate con otro relleno y cobertura ----------------------------------------- $260</p>
        <br>
        <h3>Pan Rde Velvet</h3>
        <p>Pan Red Velvet con relleno y cobertura queso crema ------------------------------------ $290 </p>
        <p>Pan Red Velvet con relleno y cobertura de chocolate turin o galletas oreo ------------- $270 </p>
        <p>Pan Red Velvet con otro relleno y cobertura  ------------------------------------------ $260 </p>
        <br>
        <h3>Pan de vainilla</h3>
        <p>Pan de vainilla con relleno y cobertura de dulce de leche ----------------------------- $270</p>
        <p>Pan de vainilla con relleno y cobertura crema pastelera con duraznos o fresas --------- $250</p>
        <p>Pan de vainilla con relleno y cobertura de  cajeta ------------------------------------ $260</p>
    </section>
    <section class="pdecoracion">
        <h2>Decoraciones extras</h2>
        <br>
        <p>Chocolates (6 chocolates turin y chocolate cobertura) ------------ $120</p>
        <p>Decorade con butter cream a escoger sabor ------------------------ $100</p>
        <p>Flores naturales comestibles colores a escoger ------------------- $80</p>
        <p>Cake topper frase a escoger -------------------------------------- $85</p>
        <p>Frutas de temporada o tu las eliges ------------------------------ $80</p>
        <p>Galletas Oreo o vainilla o decoradas ----------------------------- $90</p>
        <p>Cubierta de fondat y otrso detalles a escoger -------------------- $170 </p>
    </section>
    <section class="pedido">
        <h2>Haz tu pedido abajo</h2>
        <a  class="btn-a" href="pedido.html">Haz tu pedido aqui</a> 
    </section>
</template>

<script>
export default {
    name: "menupastCom"
}
</script>

<style scoped>
    .panes {
    font-size: 16px;
    color: #fff;
    width: 33%;
    height: 300px;
    /*padding: 30px;
    float: left; */
    background-color: #80A1D4;
    display: inline-block;
    overflow: hidden;
    margin: 0 auto;
}
.precios {
    font-size: 16px;
    color: #fff;
    width: 55%;
    height: 550px;
    /*padding: 30px;
    float: left; */
    background-color: #C0B9DD;
    display: inline-block;
    overflow: hidden;
    margin: 0 auto;
}
.pdecoracion {
    font-size: 16px;
    color: #fff;
    width: 45%;
    height: 550px;
    /*padding: 30px;
    float: left; */
    background-color: #C0B9DD;
    display: inline-block;
    overflow: hidden;
    margin: 0 auto;
}
.rellenos {
    font-size: 16px;
    color: #fff;
    width: 34%;
    height: 300px;
    /*padding: 30px;
    float: left; */
    background-color: #80A1D4;
    display: inline-block;
    overflow: hidden;
    margin: 0 auto;
}
.decoracion {
    font-size: 16px;
    color: #fff;
    width: 33%;
    height: 300px;
    /*padding: 30px;
    float: left; */
    background-color: #80A1D4;
    display: inline-block;
    overflow: hidden;
    margin: 0 auto;
}
.pedido {
    font-size: 16px;
    color: #80A1D4;
    text-align: center;
    padding: 20px;
}
.btn-a {
    display: inline-block;
    text-decoration: none;
    width: 300px;
    text-align: center;
    background-color: #80A1D4;
}

</style>