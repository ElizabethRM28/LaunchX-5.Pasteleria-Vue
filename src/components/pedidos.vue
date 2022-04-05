<template>
    <section class="titulo">
            <img src="../assets/logopasterely-chico.png" alt="">
        </section>
        <form action="" class="formulario">
            <label for="nombre" class="dato">Nombre</label>
            <br>
            <input type="text" placeholder="Nombre" required id="nombre" name="nombre" min="3">
            <br>
            <br>
            <label for="apellido" class="dato">Apellido</label>
            <br>
            <input type="text" placeholder="Apellido" required id="apellido" name="apellido" min="3">
            <br>
            <br>
            <label for="email" class="dato">Email</label>
            <br>
            <input type="email" name="email" id="email" required placeholder="email@mail.com">
            <br>
            <br>
            <label for="Dirección" class="dato">Dirección</label>
            <br>
            <input type="direccion" name="direccion" id="direccion" required placeholder="No., Calle, Colonia, Municipio">
            <br>
            <br>
            <label for="tel" class="tel">Telefono</label>
            <br>
            <input type="tel" name="tel" id="tel" required placeholder="Telefono">
            <br>
            <br>
            <label for="mensaje" class="dato">Descripción general del pastel</label>
            <br>
            <textarea name="mensajeTxt" id="mensaje" placeholder="Descripción del pastel"></textarea>
            <br>
            <br>
            <input type="submit" value="Enviar" class="button">
            <br>
            <br>
            <input type="reset" value="Borrar" class="button">
            
        </form>

</template>

<script>
export default {
    name: "pedidosCom"
}
</script>


<style scoped>
    .formulario {
    text-align: center;
}
input {
    padding: 2px;
    border-radius: 5px;
    min-width: 60px;

}
.button{
    margin-top: 12px;
    border-radius: 20px;
    padding: 5px;
}

footer {
    background-color: #ded9e2;
    font-size: small;
}
</style>