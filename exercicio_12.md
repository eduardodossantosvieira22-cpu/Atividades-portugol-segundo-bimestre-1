programa
{
	
	funcao inicio()
	{
	inteiro ano

		escreva("Informe algum ano: ")
		leia(ano)
		
	se(ano <= 0){
		 	ano = 2026
	}
	
	se(ano % 4 == 0){

		se(ano % 100 == 0){

			se(ano % 400 == 0){

				escreva("O ano é bissexto")
			}

	senao {
		escreva("O ano não é bissexto")	
			}
		}

	senao{
		escreva("O ano é bissexto")
		}
	}

	senao{
		escreva("O ano não é bissexto")
	}
}
}
