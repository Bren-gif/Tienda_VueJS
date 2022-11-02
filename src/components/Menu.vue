<template>
    <nav>
        <ul>
        <li><a href="#"><i class="fas fa-home"></i></a></li>
        <li><a href="#">Informática y Gaming</a></li>
        <li><a href="#">Televisión</a></li>
        <li><a href="#">Frigoríficos</a></li>
        <li><a href="#">Climatización</a></li>
    </ul>
    </nav>
</template>

<script>
export default {

}
</script>

<style scoped>

ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    background-color: #465657;
    margin:0 ;
    padding: 0;
    align-items: center;
}

li {
    list-style: none;
    padding: 20px 30px;
}

li:hover{
    background-color: #c46f62;
}
li:hover a {
    color: #465657;
} 

a{
    text-decoration: none;
    color: #c46f62;
    font-size: 1.1rem;
}

i{
    color: white;
}


</style>