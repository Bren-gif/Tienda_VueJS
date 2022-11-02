<template>
  <Header />
  <Menu />
  <Migas />
  <div class="producto">
    <Product-img />
    <DatosCompra />
  </div>
  <Descripcion />
  <Footer />
</template>

<script>
import Header from './components/Header.vue'
import Menu from './components/Menu.vue'
import Migas from './components/Migas.vue'
import ProductImg from './components/ProductImg.vue'
import DatosCompra from './components/DatosCompra.vue'
import Descripcion from './components/Descripcion.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Header, Menu, Migas,ProductImg, DatosCompra, Descripcion, Footer,
    

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(32, 31, 31);
  margin: 0;
}

body {
  margin: 0;
}
.producto{
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  flex-wrap: wrap;
}
</style>
