# JavaScript

Documentação para o entendimento da ferramenta **Node.js**, utilizando as formações _"JavaScript para back-end"_, _"JavaScript para front-end"_ da Alura e o curso de _"JavaScript"_ do Curso em Vídeo

# ![js50](https://user-images.githubusercontent.com/106445418/181271387-358960f0-a87b-4a7f-bd19-39f36deac11f.png) JavaScript
**JavaScript** é uma linguagem de programação de [alto nível](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/ad6b300ce71c89492671876dfe1156989de5300a/alto_nivel.md), [interpretada](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/dc89de7426c8ede4bf988eac1b3f26b48819441d/interpretada.md), com [tipagem dinâmica](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/c10e44f7c1e049e3784f0f5fdcfe9795e0be6a56/tipagem.md) e [multiparadigma](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/c195a07b668a299afe279dace7d42338068669c5/multiparadigma.md). Junto com HTML e CSS, representa a base das tecnologias para internet.
 
# ![node50](https://user-images.githubusercontent.com/106445418/181272395-b4ca04e1-bb01-427b-ad38-dfb92a4ebe05.png) Node.js
O **Node.js** é um ambiente para execução de códigos JavaScript pelo back-end.

# Instruções JavaScript

As instruções, *statements* em inglês, no JavaScript são compostas por:

- **Comentários (*Comments)***
- **Palavras-chave (k*eywords)***
- *Values*
- Operadores **(o*perators)***
- Expressions

## Comentários *(comments)* ##

```css
// comentário de uma linha
/* comentário de mais 
de uma linha */
```

## Exemplos de Palavras-chave *(keywords)* ##

| Palavra-chave | Descrição |
| --- | --- |
| [var](https://github.com/felipemadu13/JavaScript/blob/1f73ce8bf9982096ec9872733ad98d3896d24bd4/Textos/var,%20let%20e%20const.md) | Declara uma variável de escopo global. |
| [let](https://github.com/felipemadu13/JavaScript/blob/1f73ce8bf9982096ec9872733ad98d3896d24bd4/Textos/var,%20let%20e%20const.md) | Declara uma variável de escopo local. |
| [const](https://github.com/felipemadu13/JavaScript/blob/1f73ce8bf9982096ec9872733ad98d3896d24bd4/Textos/var,%20let%20e%20const.md) | Declara uma variável constante. |
| if | Marca um bloco para ser executado com condições. |
| switch | Marca um bloco  para ser executado em diferentes casos. |
| for | Marca um bloco para ser executado em um laço. |
| function | Declara uma função. |
| return | A saída deseja da função. |

## Tipos ##
Os tipos são nada mais que os **tipos de dados** que podem ser usadas em uma determinada linguagem de programação.

 última versão ECMAScript define sete tipos de dados:
 
 | TIPO | DEFINIÇÃO | EXEMPLO |
| --- | --- | --- |
| String | Textos | `let variavel = ‘exemplo de texto’; `|
| Number | Números | `let variavel = 5;` |
| Boolean | Verdadeiro (true) ou Falso (false) | `let variavel = true;` |
| Object | Basicamente, qualquer coisa. | `let variavel = documento.querySelector(’h1’);` |
| Null | Valor nulo | `let variavel = null;` |
| Undefined | Valor não definido | `undefined` |
| BigInt |  É um objeto nativo que fornece um modo de representar números inteiros maiores que 2^53 | `BigInt(valor);` |
| Symbol | Depois de criar um símbolo, seu valor é mantido privado e para uso interno. | `Symbol();` |



## Função ##

A função é um “bloco de código”  encarregado de uma tarefa que pode ser reutilizado diversas vezes por outras partes do código.

```
function imprimeTexto(texto) {
    console.log(texto)
}

imprimeTexto('Oi');
imprimeTexto('Outro texto');
```

