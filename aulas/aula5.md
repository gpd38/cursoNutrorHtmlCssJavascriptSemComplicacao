# Aula5

Aqui iremos manipular um pouco de css. Veremos a utilização dentro do próprio arquivo HTML e através de um arquivo externo.

### Tags do HTML5

	- Header: Tag utilizada para informar que é o cabeçalho da página.

	- Nav: Tag utilizada para informar que é a navegação da página ou elemento.

	- Section: Tag utilizada para informar que é o corpo da página ou elemento.

	- Footer: Tag utilizada para informae que é o rodapé da página.

### Mão na massa

	- CSS interno + HTML5

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Chronos Academy</title>
	</head>
	<body>
		<header style="text-align:center; border: 1px solid #000; height:100px; width:1200px; margin-left:auto; margin-right:auto;">
			<h1>ChronosAcademy</h1>
		</header>
		<nav style="text-align:center; border: 1px solid #000; height:70px; width:1200px; margin-left:auto; margin-right:auto;">
			<h1>Menu ChronosAcademy</h1>
		</nav>
		<section style="text-align:center; border:1px solid #000; height:700px; width:1200px; margin-left:auto; margin-right:auto;">
			Corpo ChronosAcademy
		</section>
		<footer style="text-align:center; border: 1px solid #000; height:80px; width:1200px; margin-left:auto; margin-right:auto;">
			<h1>Rodapé ChronosAcademy</h1>
		</footer>
	</body>
</html>
```

	- CSS Externo + HTML5

```CSS
.centralizaTexto{text-align: center}
.borda{border: 1px solid #000}
.centralizaMargem{margin-left: auto; margin-right: auto}
.largura{width: 1200px}

nav{height: 70px; background-color: red}
section{height: 600px}
footer{height: 80px}
```

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Chronos Academy</title>
		<link rel="stylesheet" type="text/css" href="estiloAula05.css">
	</head>
	<body>
		<header style="height:100px" class="centralizaTexto borda centralizaMargem largura">
			<h1>ChronosAcademy</h1>
		</header>
		<nav class="centralizaTexto borda centralizaMargem largura">
			<h1>Menu ChronosAcademy</h1>
		</nav>
		<section class="centralizaTexto borda centralizaMargem largura">
			Corpo ChronosAcademy
		</section>
		<footer class="centralizaTexto borda centralizaMargem largura">
			<h1>Rodapé ChronosAcademy</h1>
		</footer>
	</body>
</html>
```

### Game

- [Primeiro Lugar] - Augusto
- [Segundo Lugar] - Sidineia
- [Terceiro Lugar] - Maurício