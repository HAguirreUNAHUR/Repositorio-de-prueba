# Repositorio-de-prueba
Repositorio de prueba N°1

Calculadora 2.0

<html>
	<head>
		<script>
		function sumar (){
			var x =  parseInt(document.getElementById("sum1").value);
			var y =  parseInt(document.getElementById("sum2").value);
			var suma = x + y;
			alert ("Resultado:"  + suma);
		}
			
		</script>
	<title> CALCULADORA 2.0 </title>
	</head>
<body>
<form>

<h1>Calculadora 2.0</h1>		
Ingresar 1 <input id="sum1">	<br><br><br><br>

Ingresar 2 <input id="sum2">

<p id="sumar"></p>

<script>



</script>

	<br><br><br>
	
<button onclick ="sumar()" type ="button">sumar</button>


</form>

</body>
</html>
