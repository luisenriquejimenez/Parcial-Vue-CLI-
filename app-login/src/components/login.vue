<template>
    <center>
        <form class="formulario">
            <h2>NOMBRE</h2>
            <div class="contenedor">
                <h3>INGRESAR A CUENTA</h3>

                <div class="imput-contenedor">
                    <input type="texto" placeholder="USUARIO">

                </div>

                <div class="imput-contenedor"><br>
                    <input type="password" placeholder="CONTRASEÑA">

                </div><br>

                <button class="btn btn-dark" type="submit">INGRESAR A CUENTA</button>
                <p>olvidaste tu contraseña</p>
            </div>
        </form>
    </center>
</template>


<script>
export default {
  name: 'login',
}
</script>


<style scoped>
 body {
            background-color: #d3d3d3;
        }
        
        h2 {
            border: 5px solid black;
            color: red;
            background-color: pink;
            font-size: 30px;
        }
        
        h3 {
            color: darkgoldenrod;
            font-size: 25px;
        }
        
        form {
            background-color: white;
            padding: 30px;
            margin: 460px;
            border: 2px solid darkgoldenrod;
            border-radius: 5px;
        }
</style>
