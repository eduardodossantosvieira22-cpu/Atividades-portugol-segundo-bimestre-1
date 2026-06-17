programa
{
	
	funcao inicio()
	{
		
		inteiro n1 , n2 , n3 

		escreva("Diga três numeros prara formar um possível triangulo \n")
		leia(n1)
		leia(n2)
		leia(n3)

		se((n1 == n2) e (n2 != n3)){
			escreva("O triangulo é isosceles")
		}

		senao se((n1 != n2) e (n2 != n3) e (n1 != n3)){
			escreva("O triangulo é escaleno")
		}

		senao se((n1 == n2) e (n2 == n3)){
			escreva("O triangulo é equilatero")
			
		}
	}
}
