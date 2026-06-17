programa
{
	
	funcao inicio()
	{
		inteiro km

		escreva("O piloto passou a quantos KMs? ")
		leia(km)

		se(km > 80){
			escreva("Ele sera penalizado! \n")

			escreva("A penalidade sera de de: ", (km - 80) * 7000)
		}
	}
}
