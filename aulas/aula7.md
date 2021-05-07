# Aula7

Revisão geral e algumas dicas sobre inspecionar elementos da página.

### Mão na massa

```CSS
.centralizaTexto{text-align: center}
.borda{border: 1px solid #000}
.centralizaMargem{margin-left: auto; margin-right: auto}
.largura{max-width: 1200px; min-width: 570px;}
nav{height: 70px;}
section{height: 600px}
footer{height: 80px}
form{text-align: left; padding-left: 20%}
p{font-weight: bolder;}
textarea {
  resize: none;
  vertical-align: top;
  border-radius: 10px;
}
```

```HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Chronos Academy</title>
		<link rel="stylesheet" href="estiloAula06.css">
	</head>
	<body>
		<header style="height:100px" 
		class="centralizaTexto borda centralizaMargem largura">
			<h1>Filme Plataforma</h1>
		</header>
		<nav class="centralizaTexto borda centralizaMargem largura">
			<h1>Menu ChronosAcademy</h1>
		</nav>
		<section class="centralizaTexto borda centralizaMargem largura">
			<h1>Cadastro Filme</h1>
			<form action="#">
				<p>
					<label>
						Nome Filme:<input type="text" name="filme" placeholder="Nome Filme">
					</label>
				</p>
				<p>
					<label>
						Descrição:<textarea cols="60" rows="10"></textarea>
					</label>
				</p>
				<p>
					<label>
						Plataforma:<input list="plataforma">
						<datalist id="plataforma">
							<option value="Netflix"></option>
							<option value="Prime Video"></option>
							<option value="Disney+"></option>
						</datalist>
					</label>
				</p>
				<p>
					Categoria:
					<label>
						<input type="radio" name="categoria" value="acao">Ação
					</label>
					<label>
						<input type="radio" name="categoria" value="aventura">Aventura
					</label>
					<label>
						<input type="radio" name="categoria" value="suspense">Suspense
					</label>
					<label>
						<input type="radio" name="categoria" value="terror">Terror
					</label>
				</p>
				<p>
					<!-- Inserido o atributo value por causa do firefox -->
					<input type="submit" value="Enviar">
					<input type="reset">
				</p>
			</form>
		</section>
		<footer class="centralizaTexto borda centralizaMargem largura">
			<h1>Rodapé ChronosAcademy</h1>
		</footer>
	</body>
</html>
```

### Inspecionar elementos

No elemento que deseja identificar clique com botão direito sobre o elemento e escolha a opção "inspecionar elemento".![Inspecionar elemento Chrome x Firefox](https://github.com/gpd38/cursoNutrorHtmlCssJavascriptSemComplicacao/blob/main/img/inspecionarelementochromexfirefox.png)

Utilizando Xpath 

   - Exemplo ruim
```
//body/section/form/p[1]/label
```

   - Exemplo bom
```
//p[1]/label
```

Utilizando Css Selector

   - Exemplo ruim
```
body > section > form > p:nth-child(1) > label
```

   - Exemplo bom
```
p:nth-child(1) > label
```

### Game

- [Primeiro Lugar] - Augusto
- [Segundo Lugar] - Cícero
- [Terceiro Lugar] - Araceli