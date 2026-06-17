programa
{
	
	funcao inicio()
	{
		inteiro temperatura

		escreva("Qual a temperatura agora? ")
		leia(temperatura)

		se((temperatura > 0) e (temperatura < 25)){

			escreva("+", temperatura, " graus é bem fresquinho!")
		
		}

	se(temperatura >= 25) {
		escreva("+", temperatura, " graus é um baita calorão ein?!")
	}

	se(temperatura <= 0){

		escreva( temperatura, " graus é um frio do cão!")
	}
	}
}
