<template>
    <div class="descripcion">
        <div class="text">
            <h2>Descripción</h2>
            <p>El diseño de bisel ultraestrecho se adapta perfectamente a cualquier lugar de la casa Una mayor relación pantalla-cuerpo sin bordes molestos se traduce en una experiencia visual más envolvente y agradable, creando un sistema de cine en casa para tu salón.

            Resolución 4K UHD para disfrutar de unos gráficos impresionantes Este Smart TV de nivel de entrada cuenta con resolución 4K UHD. Con un ángulo de visión de 178°, las imágenes tienen un aspecto más nítido y con más capas, lo que proporciona una experiencia visual excepcional.
            
            MEMC para una mayor fluidez sin movimientos bruscos La tecnología MEMC añade de forma automática fotogramas artificiales en el contenido con baja velocidad de fotogramas para obtener una experiencia visual más fluida sin que se produzcan fallos en las imágenes. Esto produce una visualización perfecta, independientemente de lo que estés viendo, ya sea una película de acción o un juego de carreras</p>
        </div>
        <video src="../assets/video.mp4" width="500" height="400" controls></video>
    </div>
    
</template>

<script>
export default {

}
</script>

<style scoped>

    .descripcion{
        display: flex;
        flex-wrap: wrap;
        margin: 50px 200px;
        align-items: flex-start;
        justify-content: space-between;
    }

    h2{
        text-align: start;
        background-color: #c46f62;
        padding: 10px 20px;
        border-radius: 5px;
        margin-right: 100px;
    }
    
    p{
        text-align: start;
        margin-right: 100px;
        margin-top: 40px;
        max-width: 500px;
    }
    video {
        box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
    }

</style>