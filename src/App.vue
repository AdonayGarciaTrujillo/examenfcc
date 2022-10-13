<template>
  <header class="text-center text-white" style="background-color: greenyellow; width: 100%; text-align: center;">
		
	
		<h1>FondaF 4°A Fernando Carrera Cervantes</h1>
			

	</header>

 
    <br>
  <card nombre="Sub" descripsion="Submarino con doble carne,queso, vegetales del dia"  precio="$130.00 MXN"  > <img src="https://th.bing.com/th/id/OIP.cxGQR-lyZT31nn8MZl80lgHaFG?pid=ImgDet&rs=1" height="200" alt=""></card> 
  <card nombre="Pizza" descripsion="Pizza extra queso, con salsa de tomate y masa fresca" precio="$200.00 MXN." > <img src="https://th.bing.com/th/id/R.54c924700a5ba42a7d9d9c1a47365be0?rik=cE8FLfr%2bOiFujQ&pid=ImgRaw&r=0" height="200" alt=""> </card>
  <card nombre="Hamburguesa"  descripsion="Hamburguesa con doble carne y queso y vegetales frescos" precio="$70.00 MXN." > <img src="https://th.bing.com/th/id/OIP.6HUFt-o_KWB7n8WX3iPyCAHaEu?pid=ImgDet&rs=1" height="190" alt=""> </card>
  <card nombre="Tacos"  descripsion="Tacos de bistek con verduras y cebollines nopales"  precio="$110.00 MXN." > <img src="https://th.bing.com/th/id/OIP.MwsJNJJnl8ZoV_2LCyod5AHaE8?pid=ImgDet&rs=1" height="200" alt=""> </card>
  <card nombre="Hot Dog" descripsion="Hot dog a con pan recien horneado, salchicha tomate y cebolla, acompañado de salsa catsup, mostaza y mayonesa" precio="$90.00 MXN." > <img src="https://th.bing.com/th/id/R.b3407d664e0b9b9c0caa58a63630a25c?rik=IAwgWurNv4UAFg&pid=ImgRaw&r=0" height="180"  alt=""> </card>
  <card nombre="Cema" descripsion="Cemita poblana completa con proteina a elegir y refresco gratis " precio="$150.00 MXN."> <img src="https://sipuebla.com/blog/wp-content/uploads/2020/07/cemitas-poblanas.jpg" height="200" alt=""></card>
  
 
  
  <footer class="text-center" style="background-color: greenyellow; width: 100%; text-align: center; height: 50px; width: 100%;">
  
    <span class="copyright" style="text-align: center;">&copy;Todos los derechos reservados Fernando Carrera Cervantes 4°A</span>
 
  </footer>

</template>



<script>
    import Card from "./components/Card.vue"
    export default {
      components: {
        Card,
      },
      
    };
</script>
       
