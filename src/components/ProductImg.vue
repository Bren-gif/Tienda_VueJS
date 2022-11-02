<template>
    <section id="producto">
        <div class="peq-img">
            <a @click="cambiarFoto(1)"><img  v-bind:src="fotos[1]" alt="Tv xiaomi" copyright="cc-by-nc"></a>
            <a @click="cambiarFoto(2)"><img  v-bind:src="fotos[2]" alt="Tv xiaomi" copyright="cc-by-nc"></a>
            <a @click="cambiarFoto(3)"><img  v-bind:src="fotos[3]" alt="Tv xiaomi" copyright="cc-by-nc"></a>
            <a @click="cambiarFoto(4)"><img  v-bind:src="fotos[4]" alt="Tv xiaomi" copyright="cc-by-nc"></a>
        </div>
        <div class="gran-img"> 
            <img v-bind:src="fotos[0]" alt="Tv xiaomi">
        </div>
    </section>    
</template>

<script>
export default {
    Name: 'producto',
    data () {
        return {
            fotos: [
                require ('../assets/img2.jpg'),
                require ('../assets/img5.jpg'),
                require ('../assets/img3.jpg'),
                require ('../assets/img4.jpg'),
                require ('../assets/img1.jpg')]
        }
    },
    methods: {
        cambiarFoto(id) {
            this.fotos[0] = this.fotos[id]
        }
    }
}
</script>

<style scoped>

#producto{
    display: flex;
    flex-wrap: wrap;
    margin-left: 200px;
    margin-top: 30px;
    margin-bottom: 100px;
    align-items: center;
}

.peq-img{
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
}

.peq-img a img {
    width: 100px;
    height: 100px;
    margin-top: 30px;
    padding: 20px;
    box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
}

.gran-img {
    box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
    margin-left: 50px;
    padding: 30px 40px;
}
</style>