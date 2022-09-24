<template>
  
  <h1 style="text-align:center;">Comida rápida</h1>
  <hr />
  <h3>Luis Miguel Cruz Linares 4°A DSM</h3>
  <Card url="https://www.pequerecetas.com/wp-content/uploads/2013/07/hamburguesas-caseras-receta.jpg" nombre="Hamburguesa" descripcion="Descripcion" precio="$55.00" />
  <Card url="https://cdn.colombia.com/gastronomia/2011/08/25/pizza-margarita-3684.jpg" nombre="Pizza" descripcion="Descripcion" precio="$100.00" />
  <Card url="https://cdn2.cocinadelirante.com/sites/default/files/styles/gallerie/public/images/2020/06/papas-fritas-con-maicena-facil.jpg" nombre="Papas" descripcion="Descripcion" precio="$70.00" />
  <Card url="https://chefeel.com/chefgeneralfiles/2021/11/barbecue-grilled-hot-dogs-with-yellow-american-mustard-on-dark-wooden-background-880x541.jpg" nombre="Hog-dog" descripcion="Descripcion" precio="$35.00" />
  <Card url="https://cdn2.cocinadelirante.com/sites/default/files/styles/gallerie/public/images/2018/04/memelas-oaxaquenas-tradicionales-con-salsa-receta.jpg" nombre="Memelas" descripcion="Descripción" precio="$45.00" />
  <Card url="https://dam.cocinafacil.com.mx/wp-content/uploads/2018/03/STVariedad-de-sandwiches.jpg" nombre="Sandwich" descripcion="Descripción" precio="$60.00" />

  

  
</template>

<script>
  import Card from "./components/Card.vue"

  export default {
    components: {
      Card,
    },
  };
</script>