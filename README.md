# VistoQA
Artefatos Visto QA CX

obs: Executar a classe MaquinaTeste via Junit.

O projeto incluído nesta data, 17/04, contém a classe CalculaPreço, responsável pelos seguintes testes pendentes:

		CalculaPreco calc = new CalculaPreco();
		
								 assertEquals(0, calc.precoTotal(), 0.01);
		calc.verificaPreco("W"); assertEquals(100, calc.precoTotal(), 0.01);
		calc.verificaPreco("X"); assertEquals(160, calc.precoTotal(), 0.01);
		calc.verificaPreco("W"); assertEquals(260, calc.precoTotal(), 0.01);
		calc.verificaPreco("W"); assertEquals(320, calc.precoTotal(), 0.01);
		calc.verificaPreco("X"); assertEquals(350, calc.precoTotal(), 0.01);
