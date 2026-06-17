programa
{
	
	funcao inicio()
	{
		real numeroA, numeroB, numeroC, numeroD, numero_maiorA, numero_maiorB

		escreva("Digite 4 numeros: \n")
		leia(numeroA)
		leia(numeroB)
		leia(numeroC)
		leia(numeroD)

		se(numeroA > numeroB){
		numero_maiorA = numeroA
		}
		
		senao{
		numero_maiorA = numeroB
		}
		
		se(numeroC > numeroD){
		numero_maiorB = numeroC
		}

		senao{
		numero_maiorB = numeroD
		}

		se(numero_maiorA > numero_maiorB){
		escreva("O numero maior é ", numero_maiorA)
		}

		senao{
		escreva("O numero maior é ", numero_maiorB)
		}
	}
}
