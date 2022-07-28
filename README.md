<h1 align="center">
  <img src="https://i.ibb.co/2PK5CWd/JSBack-End.png" alt="back-end.js">
</h1>

Documentação para o entendimento da ferramenta **Node.js**, utilizando a formação _"JavaScript para back-end"_ da Alura.

# ![js50](https://user-images.githubusercontent.com/106445418/181271387-358960f0-a87b-4a7f-bd19-39f36deac11f.png) JavaScript
**JavaScript** é uma linguagem de programação de [alto nível](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/ad6b300ce71c89492671876dfe1156989de5300a/alto_nivel.md), [interpretada](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/dc89de7426c8ede4bf988eac1b3f26b48819441d/interpretada.md), com [tipagem dinâmica](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/c10e44f7c1e049e3784f0f5fdcfe9795e0be6a56/tipagem.md) e [multiparadigma](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/c195a07b668a299afe279dace7d42338068669c5/multiparadigma.md). Junto com HTML e CSS, representa a base das tecnologias para internet.
 
# ![node50](https://user-images.githubusercontent.com/106445418/181272395-b4ca04e1-bb01-427b-ad38-dfb92a4ebe05.png) Node.js
O **Node.js** é um ambiente para execução de códigos JavaScript pelo back-end.


# JavaScript: tipos, variáveis e funções #

## Tipos ##
Os tipos são nada mais que os **tipos de dados** que podem ser usadas em uma determinada linguagem de programação.

 última versão ECMAScript define sete tipos de dados:
 
 | TIPO | DEFINIÇÃO | EXEMPLO |
| --- | --- | --- |
| String | Textos | let variável = ‘exemplo de texto’; |
| Number | Números | let variável = 5; |
| Boolean | Verdadeiro (true) ou Falso (false) | let variável = true; |
| Object | Basicamente, qualquer coisa. | let variável = documento.querySelector(’h1’); |
| Null | Valor nulo | let variável = null; |
| Undefined | Valor não definido | undefined |
| BigInt |  É um objeto nativo que fornece um modo de representar números inteiros maiores que 2^53 | BigInt(valor); |
| Symbol | Depois de criar um símbolo, seu valor é mantido privado e para uso interno. | Symbol(); |

## Variáveis ##

Dentro da programação, variáveis são estruturas capazes de reter ou representar um valor ou expressão.  A partir do EcmaScript 6, o JavaScript passou a possuir três opções de declarações para variáveis.

### var ###
O var é o tipo de declaração mais antiga do JavaScript, surgindo junto com a linguagem em 1993. Esta declaração possui escopo global, por isso é necessário muito cuidado ao escolher o indicador que acompanha a variável. Seu uso é considerado por muitos má prática, por ser muito poderosa.

### let ###
O let surgiu com o ES6 e possui escopo de bloco. Caso uma declaração seja feita dentro de uma função, ela não ira afetar as que estão fora dela.

### const ###
Por mais contraditório que o nome seja, o const é uma variável constante. Seu valor não muda, uma vez declarada.

## Operadores ##


