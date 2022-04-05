<template>
    <div>
        <section class="titulo">
            <img src="../assets/logopasterely.png" alt="">
        </section>
        <section class="informacion">
            <h2>Contactanos</h2>
            <br>
            <p>Dirección: Texcoco, Estado de México <br>
               Telefono: 55 25361425 <br>
               Horario de atención: Lunes a Sabado 9:00 a.m - 7:00 p.m. <br>
               Facebook: Paster-Ely <br>
               Instagram: Paster-Ely 
            </p>
         </section>
         <section class="pedido">
             <h3>¿Tienes antojo de algo dulce?</h3> <br>
             <p>Si tienes antojo de algo dulce ven a Paster-Ely donde encontraras el pastel que te hara estar sobre la nubes</p>
             <p>Estas en el lugar indicado </p>
             <p>Dale click aqui abajo para poder recibir Ofertas</p>
             <br>
             <section class="pedido">
                <h3>Haz tu pedido abajo</h3>
                <router-link to="/pedido" class="btn-a" >Pedido</router-link>  
            </section>
         </section>
         <section class="texto">
             <br>
             <p>Todos los pasteles son hechos con materias primas de calidad y con total dedicación para su satisfacción</p>
             <br>
         </section>
    </div>
</template>


<script>
export default {
  name: 'infInicio'
 
}
</script>

<style scoped>
    .informacion {
        font-size: 18px;
        color: #fff;
        width: 50%;
        height: 330px;
        /*padding: 30px;
        float: left; */
        background-color: #75c9c8;
        display: inline-block;
        overflow: hidden;
        margin: 0 auto;
}
.pedido {
    font-size: 16px;
        color: #fff;
        width: 50%;
        height: 330px;
        /*padding: 30px;
        float: left;*/
        background-color: #75c9c8;
        display: inline-block;
        overflow: hidden;
        margin: 0 auto;
}
.texto {
    font-size: 16px;
    color: #80A1D4;
}
.pedido input[type="button"]:hover{
    background-color: #ded9e2;
    color: #fff;
}
.btn-a {
    display: inline-block;
    text-decoration: none; 
    width: 250px;
    text-align: center;
    background-color: #80A1D4;
}
</style>