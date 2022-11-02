<template>
    <footer>
        <p>Copyright 2021 - Todos los derechos reservados</p>
        <form>
            <label>Últimas ofertas</label>
            <input type="email" placeholder="Introduce tu Email">
        </form>
        <div class="redes">
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
    </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
    footer {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-between;
        padding: 30px 200px;
        background-color: #465657;
        color: white;
        margin-top: 70px;
    }

    form{
        display: flex;
        flex-wrap: wrap;
        flex-direction: column;
        align-items: flex-start;
        font-size: 1.5rem;
    }

    input{
        min-width: 400px;
        height: 30px;
        border-radius: 5px;
        border: none;
        margin-right: 10px;
        margin-top: 20px;
    }

    i{
        color:#c46f62;
        font-size: 1.5rem;
    }
</style>