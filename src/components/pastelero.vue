<template>
    <section class="titulo">
            <img src="../assets/logopasterely-chico.png" alt="">
        </section>
    <section class="informacion">
        <h1>Información del almacen de Paster-Ely</h1>
        <br>
    </section>
        <table class="panes">
            <tr>
                <th>Sabores de pan   </th>
                <th>Porción necesaria para un pastel    </th>
                <th>Porciones en almacen   </th>
            </tr>
            <tr>
                <td>Chocolate</td>
                <td>1.2 kg</td>
                <td>6</td>
            </tr>
            <tr>
                <td>Vainilla</td>
                <td>1.2 kg</td>
                <td>9</td>
            </tr>
            <tr>
                <td>Red velvet</td>
                <td>1.2 kg</td>
                <td>3</td>
            </tr>
        </table>
        <br>
        <br> 
        <table class="adornos">
            <tr>
                <th>Adorno</th>
                <th>No. en almacen</th>
            </tr>
            <tr>
                <td>Flores</td>
                <td>50 piezas</td>
            </tr>
            <tr>
                <td>Chocolates</td>
                <td>35 piezas</td>
            </tr>
            <tr>
                <td>Fondant</td>
                <td>10 piezas</td>
            </tr>
            <tr>
                <td>Galletas</td>
                <td>5 piezas</td>
            </tr>
            <tr>
                <td>Frutas</td>
                <td>35 piezas</td>
            </tr>
            <tr>
                <td>Cake tooper</td>
                <td> 25 piezas</td>
            </tr>
            <tr>
                <td>Butter cream</td>
                <td>10 piezas</td>
            </tr>
        </table>
        <br>
        <table class="formulario">
            <tr>
                <th>Nombre</th>
                <th>Apellido</th>
                <th>E-mail</th>
                <th>Dirección</th>
                <th>Telefono</th>
                <th>Descripción de pedido</th>
            </tr>
            <tr>
                <td>Felipe</td>
                <td>Lopez</td>
                <td>felipe325@gmail.com</td>
                <td>Santa Ines 231 Iztapalapa CDMX</td>
                <td>5520362158</td>
                <td>Pan de choccolate, con galletas oreo y butter cream </td>
            </tr>
        </table>
        <br>
</template>

<script>
export default {
  name: 'pasteleroCom'
}
</script>


<style scoped>
h1 {
    text-align: center;
}
table {
    width: 100%;
}


</style>