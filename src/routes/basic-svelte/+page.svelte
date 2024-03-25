<script>
    let name = "world";
    let src = "/favicon.png";
</script>

<h1>Basic svelte</h1>

<p>
	Svelte esta compuesto por bloques de HTML, CSS and JavaScript que estan encapsulados bajo la
	extension `.svlete`
</p>

<p>Ejemplo de uso de script: "hello {name}"</p>


<p>Podemos editar atributos de elemtos html, por ejemplo la siguiente etiqueta: </p>
<p>Si el atributo y el nombre de la variable coninciden podemos acortar en este ejemplo a esto '{'{src}'}'</p>
<img src={src} alt="logo de svelte"/>
<img {src} alt="logo de svelte sin signo ="/>
