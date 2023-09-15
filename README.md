programa
{
	
	funcao inicio()
	{
		inteiro numero,somaImpar=0,somaPar=0,controle = 1,valor

		

		enquanto (controle < 5 ){
	
			escreva("\nDigite o " + controle + "° valor : ")				
			leia(numero)
			
			se (numero % 2 == 1 ){
				escreva("Esse número é Par\n")

				somaPar = somaPar + numero
				
				}
			
					senao {

						escreva("Esse número é Ímpar\n")

						somaImpar = somaImpar + numero
				
				}
						controle ++
			}		
					escreva("\n#############################\n")
					escreva("\nA soma dos números Pares : ",somaPar)
					escreva("\nA soma dos números Ímpares: ",somaImpar)
	
	}
}# exercicioPortugol3
