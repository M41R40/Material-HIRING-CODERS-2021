
O computador sempre faz aquilo que é informado a ele.

## Algoritmos

Sequencia finita de passos (limitadas), com o objetivo de resolução de problemas.
Ex: receita de um bolo.

- Transforma uma informação.

- tem uma sequencia finitas de passos.

- é ordenada.

- resolve um problema.

é importante ser especifico na elaboração de receitas ou algoritmos.

todo programa possui.
- entrada: tudo que preciso fornecer para o computador. ex: um programa que reconhece informações para validação.

- processamento: sequencia de passos necessarios para cumprir o que se pede o algoritmo.

- saída: o resultado esperado.





## Variaveis e Operações

Espaço de armazenamento de memoria, onde fica armazenado uma informação com sua qualificação e quantificação.

qualificação : inteiro, float, var, real.

quantificar : tamanho, ocupação da memoria. bytes.

todo nome de variavel deve começar com letras.

o exemplo a seguir é executado no portugol.
```sh
programa
{
	funcao inicio() {
		inteiro var1
		real var2
		cadeia var3

		escreva("Digite um numero inteiro: ")
		leia(var1)
		escreva("Agora digite um numero real: ")
		leia(var2)
		escreva("Finalmente digite um texto: ")
		leia(var3)
		escreva("Você digitou os seguintes valores\n")
		escreva(var1 + "\n" + var2 + "\n" + var3)
  }
}

>>SAÍDA
>Digite um numero inteiro: 20
>Agora digite um numero real: 20.30
>Finalmente digite um texto: maira
>Você digitou os seguintes valores
20
20.3
maira
Programa finalizado. Tempo de execução: 13408 milissegundos

```




## Decisões
Uma decisão indica uma pergunta realizada para solucionar um problema, normalmente já havendo duas respostas, sim/verdadeira ou não/falso. Costuma ser representado por uma estrutura de algoritmo.

```sh
programa
{

	funcao inicio()
{
		escreva("Olá Mundo \n")
		real nota1, nota2, media

		escreva("Digite a nota 1: ")
		leia(nota1)
		escreva("Digite a nota 2: ")
		leia(nota2)

		media = (nota1 + nota2) / 2

		escreva("A media vale = "+media+"\n")

		se (media >= 6.0){
			escreva("Parabens voce foi aprovado! \n")
		}
		senao{
			escreva("Voce foi reprovado. \n")
		}

		escreva("Fim do programa\n")

	}
}
>>SAÍDA
>Olá Mundo
>Digite a nota 1: 10
>Digite a nota 2: 1
A media vale = 5.5
Você foi reprovado.
Fim do programa

Programa finalizado. Tempo de execução: 4613 milissegundos

```
Ainda é possível trabalhar com números de diversas formas com a logica de programação.

```sh
programa
{
	funcao inicio()
 {

		inteiro valor1, valor2, res
		escreva ("digite um valor: ")
		leia(valor1)
		escreva("digite outro valor: ")
		leia(valor2)

		res = valor1 + valor2
		escreva("Resultado da soma ="+res+"\n")

		res = valor1 - valor2
		escreva("Resultado da subtração = "+res+"\n")

		res = valor1 * valor2
		escreva("Resultado da multiplicação = "+res+"\n")

		res = valor1 / valor2
		escreva("Resultado da divisão = "+res+"\n")


	}
}


>> SAÍDA
>digite um valor: 20
>digite outro valor: 3
>Resultado da soma =23
Resultado da subtração = 17
Resultado da multiplicação = 60
Resultado da divisão = 6

Programa finalizado. Tempo de execução: 10579 milissegundos
```
 Programa basico de conversao de dias em anos.

 ```sh
 programa
{

	funcao inicio()
	{
		inteiro idade, anos, meses, dias, sobra


		//entrada a entrada em dias
		escreva("Digite sua idade em dias:")
		leia(idade)


		//processamento: dividir a idade por 365
		anos = idade / 365


		//a partir da sobra da divisao anterior, fazer o seguinte:
		sobra = idade % 365


		//dividir o valor que sobrou por 30 e obter a quantidade
		//de meses ja que 1 mes igual a 30 dias
		meses = sobra / 30


		// finalmente pegar a sobra da divisao anterior que ira
		//resultar na quantidade de dias
		dias = sobra % 30


		//exibir a saída
		escreva(anos + " anos\n")
		escreva(meses + " meses\n")
		escreva(dias + " dias\n")
	}
}
```






## Repetições
As repetições são laços importantes, já que só se cria um Software para fazer ações repetitivas.

while = enquanto.
A função enquanto é acionada quando entre chaves {} depois de uma ação eu solicito que seja repitido ate a condição ser admitida.
Ex: cod de tabuada.

```sh
programa
{

	funcao inicio()
	{
		inteiro num, contador, resultado

		escreva("qual tabuada? ")
		leia(num)

		contador = 0

		enquanto (contador <= 10){
			resultado = num * contador
			escreva(num + " x " + contador + " = " + resultado + "\n")
			contador = contador + 1
	}

	}
}
>>SAÍDA
qual tabuada? 5
5 x 0 = 0
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50

Programa finalizado. Tempo de execução: 2010 milissegundos

```

for = para
```sh
programa
{

	funcao inicio()
	{
		inteiro num, contador, resultado

		escreva("qual tabuada? ")
		leia(num)

		para (contador = 0 ; contador <= 10; contador = contador + 1){
			resultado = contador * num
			escreva(num + " x " + contador + " = " + resultado + "\n")

		}
	}
}

>> SAÍDA
qual tabuada? 5
5 x 0 = 0
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50

Programa finalizado. Tempo de execução: 3539 milissegundos
```
