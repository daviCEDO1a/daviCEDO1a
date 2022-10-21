<title>Como deixar o flip na base?</title>
<body>
	<header>
		<h1 class="titulo-principal">Como deixar o flip na base?</h1>
	</header>
	<img id="banner" src="banner.jpg">
	<div class="principal">
		<h2 class="titulo-centralizado">fliping...</h2>
 
		<p>Localizada no coração da cidade a <strong>Barbearia Alura</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</p>

		<p id="missao"><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>

		<p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
	</div>

	<div class="beneficios">
		<h3 class="titulo-centralizado">Benefícios</h3>

		<ul>
			<li class="itens">Atendimento aos Clientes</li>
			<li class="itens">Espaço diferenciado</li>
			<li class="itens">Localização</li>
			<li class="itens">Profissionais Qualificados</li>
		</ul>

		<img src="beneficios.jpg" class="imagembeneficios">
	</div>
</body>
<title>Produtos - Barbearia Alura</title>
	<link rel="stylesheet" href="reset.css">
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<div class="caixa">
			<h1><img src="logo.png"></h1>

			<nav>
				<ul>
					<li><a href="index.html">Home</a></li>
					<li><a href="produtos.html">Produtos</a></li>
					<li><a href="contato.html">Contato</a></li>
				</ul>
			</nav>
		</div>
	</header>

	<main>
		<ul class="produtos">
			<li>
				<h2>Cabelo</h2>
				<img src="cabelo.jpg">
				<p class="produto-descricao">Na tesoura ou máquina, como o cliente preferir</p>
				<p class="produto-preco">R$ 25,00</p>
			</li>
			<li>
				<h2>Barba</h2>
				<img src="barba.jpg">
				<p class="produto-descricao">Corte e desenho profissional de barba</p>
				<p class="produto-preco">R$ 18,00</p>
			</li>
			<li>
				<h2>Cabelo + Barba</h2>
				<img src="cabelo+barba.jpg">
				<p class="produto-descricao">Pacote completo de cabelo e barba</p>
				<p class="produto-preco">R$ 35,00</p>
			</li>
		</ul>
	</main>

	<footer>
		<img src="logo-branco.png">
		<p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
	</footer>
</body>
<title>Contato - Barbearia Alura</title>
	<link rel="stylesheet" href="reset.css">
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<div class="caixa">
			<h1><img src="logo.png"></h1>

			<nav>
				<ul>
					<li><a href="index.html">Home</a></li>
					<li><a href="produtos.html">Produtos</a></li>
					<li><a href="contato.html">Contato</a></li>
				</ul>
			</nav>
		</div>
	</header>

	<main>
		<form>
			<label for="nomesobrenome">Nome e sobrenome</label>
			<input type="text" id="nomesobrenome" class="input-padrao">

			<label for="email">Email</label>
			<input type="text" id="email" class="input-padrao">

			<label for="telefone">Telefone</label>
			<input type="text" id="telefone" class="input-padrao">

			<label for="mensagem">Mensagem</label>
			<textarea cols="70" rows="10" id="mensagem" class="input-padrao"></textarea>

			<div>
				<p>Como prefere o nosso contato?</p>
				<label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email"> Email</label>
				
				<label for="radio-telefone"><input type="radio" name="contato" value="telefone" id="radio-telefone"> Telefone</label>
				
				<label for="radio-whatsapp"><input type="radio" name="contato" value="whatsapp" id="radio-whatsapp"> WhatsApp</label>
			</div>

			<div>
				<p>Qual horário prefere ser atendido?</p>
				<select>
					<option>Manhã</option>
					<option>Tarde</option>
					<option>Noite</option>
				</select>
			</div>

			<label class="checkbox"><input type="checkbox">Gostaria de receber nossas novidades por email?</label>

			<input type="submit" value="Enviar formulário">
		</form>
	</main>

	<footer>
		<img src="logo-branco.png">
		<p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
	</footer>
</body>
