programa
{
	
	funcao inicio()
	{
		inteiro dias = 0
		real km = 0.0

		escreva("Por quantos dias você alugou o carro? ")
		leia(dias)

		escreva("E quantos KMs? ")
		leia(km)

		escreva("O  total a pagar ficou: ", (dias * 60) + (km * 0.15))
	}
}
