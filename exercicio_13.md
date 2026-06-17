programa
{
	
	funcao inicio()

	{	inteiro codigo = 0
		inteiro quantidade = 0
		real preco = 0.0
		real total = 0.0
	
	
		escreva("Cachorro quente..........100 \n")
		escreva("Bauru....................101 \n")
		escreva("Bauru c/ovo..............102 \n")
		escreva("Hamburger................103 \n")
		escreva("Cheeseburger.............104 \n")
		escreva("Refrigerante.............105 \n")
		escreva("Semente dos Deuses.......106 \n")

		escreva("Digite o codigo de algum lanche: ")
		leia(codigo)

		escreva("E a quantidade: ")
		leia(quantidade)

		
		escolha(codigo){
			
			
			caso  100:{
				preco = 5.00
				pare
			}

			caso 101:{
				preco = 2.60
				pare
			}

			caso 102:{
				preco = 3.80
				pare
			}

			caso 103:{
				preco = 9.00
				pare
			}

			caso 104:{
				preco = 11.00
				pare
			}

			caso 105:{
				preco = 3.00
				pare
			}

			caso 106:{
				preco = 1000.0
				pare
			}

		
		}

		total = preco * quantidade

		escreva(quantidade,",", codigo, " vai ficar: ", total)
	}
}
