<template>
    <header>
        <div class="logo">
            <h1>ELECTRO<span>MUNDO</span></h1>
        </div>
        <form>
            <input id="buscar" type="search" placeholder="Buscar tu producto">
            <input id="bt-buscar" type="button" value="Buscar">
        </form>
        <div class="registrar">
            <button>
            <a href="#">Registrar</a>
        </button>
        <button>
            <a href="#">Iniciar Sesión</a>
        </button>
        </div>
    </header>
</template>

<script>

export default ({
    
})
</script>


<style scoped>

header{
    display: flex;
    align-items: center;
    padding:40px 200px ;
    background-color: #c46f62;
    justify-content: space-around;
    flex-wrap: wrap;

}

h1 {
    margin: 0;
    color: white;
}

span {
    color:#465657 ;
}

form {
    flex-grow: 1;
}

#buscar {
    min-width: 400px;
    height: 30px;
    border-radius: 5px;
    border: none;
    margin-right: 10px;
}

#bt-buscar {
    background-color: #465657;
    border: none;
    border-radius: 5px;
    margin-right: 10px;
    padding:8px 15px;
    color: #c46f62;
}

a{
    text-decoration: none;
    color: #c46f62;
    font-size: 1.1rem;   
}

button {
    background-color: #465657;
    border: none;
    border-radius: 5px;
    margin-right: 10px;
    padding:5px 15px;
}

</style>