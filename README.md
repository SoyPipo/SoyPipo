- 👋 Hi, I’m @SoyPipo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
SoyPipo/SoyPipo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<html>
	<head>
		<link rel="stylesheet" type="text/css" href="barato.css">
		<title> Black Friday </title>
	</head>
	<body>
	<div class="titulo">
		<h1> EQUIPO SOÑADO </h1>
	</div>
	<br>
	<hr>
	<hr>
	<p> 
		Gracias por elegirnos para poder elegir los componentes de tu equipo soñado, a continuación, te dejaremos un formulario
		quenos gustaria que rellenases con total sinceridad para poder ayudarte en todo lo posible.
	</p>
	<p> 
		Completa el formulario y una vez lo tengas nos pondremos en contacto contigo:
	</p>
	<hr>
	<hr>
	<br>
	<fieldset>
		<legend> RELLENAR FORMULARIO </legend>
			<form>
			<ul>
				<p class="negrita"> Nombre Completo <span>*</span>
					<label for="nombre"> <input type="text" name="nombre" id="nombre1" size="10" placeholder="Nombre"> 
					<label for="apellido"> <input type="text" name="apellido" id="nombre1" size="15" placeholder="Apellido">  
				</p>
				<h4> <i>PROCESADORES </i> </h4>
				<p class="negrita"> Tipo de procesador <span>*</span> 
					<ul> 
						<input type="radio" name="intel" value="intel">INTEL<br>
						<label for="intel">
						<input type="radio" name="amd" value="amd">AMD<br>
						<label for="amd">
					</ul>
				</p>
				<br>
				<label for="generación"> <p class="negrita"> Selecciones la generación <span>*</span>  </label>
					<select name="generación">
					  <option selected>...</option>
					  <optgroup label="AMD">
						<option value="1º">1º Generacíon</option>
						<option value="2º">2º Generacíon</option>
						<option value="3º">3º Generacíon</option>
						<option value="4º">4º Generacíon</option>
						<option value="5º">5º Generacíon</option>
					  </optgroup>
					  <optgroup label="INTEL">
						<option value="1º">1º Generacíon</option>
						<option value="2º">2º Generacíon</option>
						<option value="3º">3º Generacíon</option>
						<option value="4º">4º Generacíon</option>
						<option value="5º">5º Generacíon</option>
						<option value="6º">6º Generacíon</option>
						<option value="7º">7º Generacíon</option>
						<option value="8º">8º Generacíon</option>
						<option value="9º">9º Generacíon</option>
						<option value="10º">10º Generacíon</option>
					  </optgroup>
					</select>
				<h4> <i>RGB</i> </h4>
				<p class="negrita"> ¿Quiere luces <i>RGB</i> en su equipo? <span>*</span>
					<ul>
						<input type="checkbox" name="rgb" id="rgb"> Si
						<label for="rgb"><br>
						<input type="checkbox" name="rgb" id="rgb"> No
						<label for="rgb">
					</ul>
				</p>
				<p> 
					* Si su repuesta ha sido <b>si</b> indique que intensidad quiere de luces RGB, porfavor. <br>
					De lo contrario puede pasar a la siguiente pregunta.
					<ul>
						<p>
							*Mientras la barra este mas a la izquierda mas RGB tendra.
						</p>
						<input type="range" name="rango" min="1" max="6" list="intensidad rgb" size="35">
						<datalist id="intensidad">
						  <option value="1" label="Poco">
						  <option value="2" label="Mucho">
						  <option value="3" label="Nunca es suficiente">
						</datalist>
					</ul>
				</p>
				<br>
				<p class="negrita"> Dirección<span>*</span>
					<label for="calle"> <input type="text" name="calle" id="calle" size="18" placeholder="Calle"> 
				</p>
				<br>
				<p class="negrita"> Coódigo Postas<span>*</span>
					<label for="calle"> <input type="text" name="calle" id="calle" size="18" placeholder="12345" maxlength="5"> 
				</p>
				<br>
				<input type="reset" value="Resetear el formulario" id="identificador">
			</ul>
	</fieldset>
	
	</body>
</html>
