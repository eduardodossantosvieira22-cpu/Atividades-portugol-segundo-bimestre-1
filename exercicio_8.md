programa
{
	
	funcao inicio()
	{
		inteiro n1, n2, n3

		escreva("Digite 3 numeros: \n")
		leia(n1)
		leia(n2)
		leia(n3)

	se((n1 >= n2) e (n2 >= n3)){
		escreva(n1,",", n2,",", n3)
		}
	senao se((n1 >= n3) e (n3 >= n2)){
		escreva(n1,",", n3,",", n2)
		}
	senao se((n2 >= n1) e (n1 >= n3)){
		escreva(n2,",", n1,",", n3)
		}
	senao se((n2 >= n3) e (n3 >= n1)){
		escreva(n2,",", n3,",", n1)
		}
	senao se((n3 >= n1) e (n1 >= n2)){
		escreva(n3,",", n1,",", n2)
		}
	senao {
		escreva(n3,",", n2,",", n1)
	}
	}
}
