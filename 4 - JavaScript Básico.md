##  Oque é JavaScript?

É uma linguagem de programação popular atualmente, conhecida
como a linguagem da internet porque os navegadores a entendem de modo nativo sem a instalação de plugin.

#### Arquivo index

Apesar do js ser uma considerada uma linguagem de programação interpretada estruturada, de script em alto nível com tipagem dinâmica fraca e multiparadigma. Juntamente com HTML e CSS, o JavaScript é uma das três principais tecnologias da World Wide Web.






## Variáveis

São usadas para armazenar dados, que podem ser atualizados ou recuperados sempre que necessario.

#### Criando variaveis

Para declarar uma variavel use um dos comandos:
- O comando **var** é editavel e considerado um escopo global.

```JavaScript
var nome_da_variavel = "valor";
```
- O comando let não realiza ações fora do escopo local, simbolizado por {chaves}.

```JavaScript
let nome_da_variavel = "valor"
```

- O comando **const** é  semelhante ao let. O valor de uma constante não pode ser alterado por uma atribuição, e ela não pode ser redeclarada.

```JavaScript
const nome_da_variavel = "valor";
```

#### Exibindo texto.

Para exibir o valor da variavel use o comando:
```JavaScript
console.log(nome_da_variavel)
```







## Tipos de dados

O tipo de dado em Javascript pode ser alterado conforme a necessidade do algoritmo.

Todo texto adicionado em um valor de uma variavel é considerado **String**.

Todo numero é considerado do tipo **number** ou **float**


Um valor vazio ou nulo é considerado um dado do tipo **null**

Um dado com um valor não verificado ou não reconhecido é considerado **underfund**


Para declarar um conjunto de informações ou strings, usa o conjunto de dados do tipo **object** declarando entre {chaves}

Para responder a uma condição, sim ou não representado por verdadeiro ou falso, declara-se um tipo de dados **boolean**

Um conjunto de dados que precisa de ação é declarado como uma função, é do tipo **array**

Para saber o tipo do dado inserido na variavel use o operador **typeof**








## Operadores aritméticos

Adição : +

```JavaScript
var nome_da_variavel = 1+3
```

Subtração: -

Multiplicação: *

Divisão: /

modulo ou resto de uma divisão : %

incremento : ++

decremento : --









## Condicionais
Como em todas as linguagens de programação, Javscript tambem possui condições para responder questões verdadeiras ou falsas.

Usa- se os comandos: if, else if, else e o switch.

A condicional if  é uma estrutura condicional que executa a afirmação, dentro do bloco, se determinada condição for verdadeira.

Se for falsa, executa as afirmações dentro de else.

O switch é uma condicional que refere-se a casos, representado pela palavra case, para verificar um caso, porem é necessário utilizar um break, pois a condicional não para sozinha.
#### Exemplo switch
```JavaScript
var mes = "janeiro"

switch (mes) {
    case "fevereiro":
        console.log("mes 2");
        break;
    case "março":
        console.log("mes 3");
        break;
    case "dezembro":
        console.log("mes 12");
        break;
    default:
        console.log("nenhum dos casos acima foi atendido");

}
```







## Estrutura de Repetição
Você pode pensar em um laço de repetição como um jogo onde você manda o seu personagem andar X passos em uma direção e Y passos em outra.

#### for
O comando **for** traduz do ingles o **para**, é uma estrutura de repetição para executar a ação pela suas delimitações.
```JavaScript
var colors = ["black"]
```
#### while
O comando **while** traduz do ingles **enquanto** realiza a ação enquanto a afirmação for verdadeira.
```JavaScript
var i = 0

while (i <10) {
        console.log(i);
        i++;
}
```
Para incremento foi utilizado o ++, ele

#### do
O comando **do** traduz do ingles **fazer** irá seguir a mesma ideia do while de executar sobre afirmação verdadeira, porem usando o do se verifica depois a afirmação.
```JavaScript
var i = 1;

do {
    console.log(i);
    i++;
} while (i < 10);
```







## Funções
Representada em JavaScript pelo comando **function** + nome_da_função( ).

Necessitando que no final do codigo seja chamada pelo nome_da_função( );


Em sua maioria as funções tem o poder de executar ações no codigo, então o trecho do codigo que cita faça aquilo ou isso é uma função.

```JavaScript
function um(name) {
    console.log('Hello ' + name)
}
um("Maíra Daiana Fernandes");
```





## Classes

Representado pelo comando **class**, seguido de um nome_da_classe. O codigo que contem class contem objetos, são designados quais na class e depois executados com a criação de uma variavel com todas as respostas para os objetos criados.
```JavaScript
class book {
  constructor(title, author, pages) {
    this.title = title;
    this.author = author;
    this.pages = pages;
  }

  read() {
    return `Estou lendo ${thi.title}`
  }
}
// preenchimento dos campos criados, com novos objetos
let book = new Book('Marley and me', 'i dont know', 500);
let otherbook = new Book('Sitio do picapau amarelo','monteiro lobato',300);

console.log(book, otherbook)
```

#### Reaproveitando codigo.
Para não precisar copiar o codigo todo para repetir o processo só que em outra classe, existe o comando **extends**, que vai usar a estrutura de informações daquela parte do codigo.

No mesmo codigo repare o aproveitamento:
```JavaScript






## Exercícios
