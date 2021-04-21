# Aula3

### Principais elementos de um formulário

 - label
 - input
 - select
 - list e datalist
 - textArea
 - button
 - fielset e legend

### Mão na massa

<!DOCTYPE html>
<html>
	<head>
		<title>Chronos Academy</title>
	</head>
	<body>
		<form action="#">
			<label for="name">Nome:</label>
			<input type="text" name="i_name" />
			<br>
			<label for="password">Password:</label>
			<input type="password" name="i_password" />
			<br>
			<label>Hidden:</label>
			<input type="hidden" name="i_hidden" />
			<br>
			<label>File:</label>
			<input type="file" name="i_file" />
			<br>
			<label>Sexo:</label>
			Masculino<input type="radio" name="sexo" />
			Feminino<input type="radio" name="sexo" />
			<br>
			<label>Filme:</label>
			Ação<input type="checkbox" name="acao" />
			Aventura<input type="checkbox" name="aventura" />
			<br><br>

			Inputs do HTML5
			<br>
			E-mail:<input type="email">
			<br>
			Number:<input type="number">
			<br>
			URL:<input type="url">
			<br>
			Search:<input type="search">
			<br>
			Telefone:<input type="telefone">
			<br><br>

			Date:<input type="date">
			<br>
			DateTime-Local:<input type="datetime-local">
			<br>
			Month:<input type="month">
			<br>
			Time:<input type="time">
			<br>
			Week:<input type="week">
			<br><br>

			Color:<input type="color">
			<br>
			Range:<input type="range">
			<br><br>

			TextArea:<textarea rows="5" cols="50"></textarea>
			<br>
			Button:<button>Botão</button>
			<br><br>

			Select:
			<select>
				<option value="Java">JavaAAA</option>
				<option value="C#">C Sharp</option>
				<option value="js">JavaScript</option>
			</select>
			<br><br>

			List:
			<input list="linguagens">
			<datalist id="linguagens">
				<option value="Java"></option>
				<option value="C#"></option>
				<option value="js"></option>
			</datalist>
			<br><br>

			Fieldset:
			<fieldset>
				<legend>
					Select:
					<select>
						<option value="Java">JavaAAA</option>
						<option value="C#">C Sharp</option>
						<option value="js">JavaScript</option>
					</select>
					<br><br>

					List:
					<input list="linguagens">
					<datalist id="linguagens">
						<option value="Java"></option>
						<option value="C#"></option>
						<option value="js"></option>
					</datalist>
					<br><br>
				</legend>
			</fieldset>

			<br><br>
			<input type="reset" name="reset" value="Redefinir">
			<input type="submit" name="submit" value="Enviar">
			<br>
		</form>		
	</body>
</html>

###Game

- [Primeiro Lugar] - MS
- [Segundo Lugar] - Paula
- [Terceiro Lugar] - Augustus118