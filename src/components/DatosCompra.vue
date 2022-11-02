<template>
    <section id="producto">
        <h1>Tv 55" xiaomi P1E - UHD 4K Smart TV</h1>
        <div class="datos">
            <div class="precio">
                <h3> Precio 430€</h3>
                <div class="wrapper">
                    <button class="btn" @click="cambiarContador('-1')" type="button" name="button">-</button>
                    <input class="cantidad" type="text" name="name" :value="contador">
                    <button class="btn" @click="cambiarContador('1')" type="button" name="button">+</button>
                </div>
            </div> 
            
            <div class="bt-comprar">
            <button class="boton">Comprar</button>
            <button class="boton">Añadir al carrito</button>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    Name: 'ProductoDatos',
    data () {
        return {
            contador: 1
        }
    },
    methods: {
        cambiarContador(num) {
            this.contador += +num;
            if (!isNaN(this.contador) && (this.contador < 0)) {
                this.contador = 0
            }
        }
    }
}
</script>


<style scoped>

#producto{
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    margin-right: 200px;
    justify-content: start;
}

.datos{
    display: flex;
    flex-wrap: wrap;
    align-items: flex-end;
    justify-content: space-between;
}

.bt-comprar{
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
}

button{
    background-color: #c46f62;
    border: none;
    border-radius: 5px;
    margin-right: 10px;
    padding:5px 15px;
    color: #465657;
    font-size: 1.2rem;
    margin-top: 20px;
}

input{
    width: 25px;
    height: 25px;
    text-align: center;
    margin:0 20px;
}

.btn{
    margin: 0;
}

h3 {
    text-align: start;
    color:#c46f62;
}

h1{
    margin-top: 90px;
}


</style>