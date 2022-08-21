# JavaScript

Documentação para o entendimento da linguagem JavaScript.

# ![js50](https://user-images.githubusercontent.com/106445418/181271387-358960f0-a87b-4a7f-bd19-39f36deac11f.png) JavaScript
**JavaScript** é uma linguagem de programação de [alto nível](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/ad6b300ce71c89492671876dfe1156989de5300a/alto_nivel.md), [interpretada](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/dc89de7426c8ede4bf988eac1b3f26b48819441d/interpretada.md), com [tipagem dinâmica](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/c10e44f7c1e049e3784f0f5fdcfe9795e0be6a56/tipagem.md) e [multiparadigma](https://github.com/felipemadu13/Alura_JavaScript_Back_End/blob/c195a07b668a299afe279dace7d42338068669c5/multiparadigma.md). Junto com HTML e CSS, representa a base das tecnologias para internet.
 
# ![node50](https://user-images.githubusercontent.com/106445418/181272395-b4ca04e1-bb01-427b-ad38-dfb92a4ebe05.png) Node.js
O **Node.js** é um ambiente para execução de códigos JavaScript pelo back-end.

# Sintaxe
![Syntax](https://user-images.githubusercontent.com/106445418/185790522-25fa2585-42a7-4b05-8078-c28314c8fd1d.png)

# Statement

As instruções, *statements* nas linguagens de programação, no caso do JavaScript, são compostas por:

- Comentários _(comments)_
- Palavras-chave _(keywords)_
- Valores _(Values)_
- Operadores _(operators)_
- Expressões _(Expressions)_

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
| [function](https://github.com/felipemadu13/JavaScript/blob/e22eb40968702f0e08a6b3acfdcab2e7e8f9cbbe/Textos/function.md) | Declara uma função. |
| return | A saída deseja da função. |

## Tipos ##
![Data Type](https://user-images.githubusercontent.com/106445418/185791604-12b46678-2ad3-4d8f-b534-47e4a15a9eda.png)

Os tipos são nada mais que os **tipos de dados** que podem ser usadas em uma determinada linguagem de programação.

 A última versão ECMAScript define oito tipos de dados:
 
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

## Bibliografia ##
### Cursos ###
* **JavaScript** _(Curso em Vídeo)_
* **JavaScript: tipos, variáveis e funções** _(Alura)_
* **JavaScript: Arrays** _(Alura)_
### Documentação ###
* **W3Schools**
* **MDN web docs**
