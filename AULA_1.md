[Retornar](README.md)

# Marcação do primeiro texto

## O que vamos aprender?

* Desenvolver uma página na web;

* Inserir um texto em uma página;

* Formatar o texto fazendo uso das tags do HTML;

____
### Iniciar a linguagem no HTML.

Para aprendermos a construir uma página da web, utilizaremos o exemplo da Barbearia Alura. Criaremos o texto da página fazendo uso da linguagem HTML. Antes, faça o download do texto--base da página da Barbearia Alura, que é um exemplo de um conteúdo com três parágrafos e um título.

Para aprendermos a construir uma página da web, utilizaremos o exemplo da Barbearia Alura. Vamos criar o texto da página sob os parâmetros da linguagem HTML. Antes, faça o download do texto-base da página da Barbearia Alura, que contém três parágrafos e um título. Clique no link de cor azul.

* Salve o arquivo nomeado como texto-base.zip na área de
trabalho do Windows;

* Ao abrir a pasta, localize o documento de texto;

* Depois de aberto o documento, o texto a seguir, deverá aparecer:

* Copie o texto para o Word.

Todas as páginas da web possuem algum tipo de texto. Logo, o primeiro passo para construir a página será aprender a formatar o parágrafo e os títulos. De modo geral, formatamos um texto qualquer empregando um editor de texto como o Word, por exemplo. Por meio dele, podemos alterar o tipo de fonte, seu tamanho, deixá-la em negrito ou itálico. Realize algumas formatações do estilo do texto com o Word e salve.

Quando construímos páginas para a internet, precisamos usar editores específicos para o texto. Há diversas opções de editores: o Atom, Visual Studio Code e Sublime Text 3, entre outros. Vamos utilizar o Sublime Text 3, que é gratuito e está disponível para diversos sistemas operacionais. 
* Para fazer o download, clique no link: https://www.sublimetext.com/3. 
* Escolha a versão de acordo com o seu sistema operacional.

Após realizar o download do Sublime Text 3, abriremos o programa e iremos copiar o texto do Word para ele. Vamos notar que todo o padrão de formatação feita anteriormente será perdida ao colar no Sublime Text 3.

Salve o texto do Sublime Text 3 em uma pasta ou na área de trabalho nomeando-a como index.html.

Os arquivos nomeados com a extensão .html significam que são páginas da web.

Ao retornarmos à área de trabalho do Windows, veremos o arquivo salvo como um ícone do Chrome ou do seu navegador padrão.

Ao darmos um duplo clique no ícone, o texto será aberto no navegador de internet padrão do computador. Porém, aparecerá sem a formatação que fizemos antes. Podemos observar que não há título ou divisão entre os parágrafos.

Uma página da internet tem seu conteúdo definido através da linguagem HTML, que é a sigla, em inglês, para hyper text markeup language, que significa linguagem de marcação de hipertexto.
Um marcador é um comando de formatação da linguagem. No HTML, iremos aplicar marcadores chamados de tags (marcadores, em inglês).
O formato de uma tag é o sinal de “<” (menor) seguido de um comando e fechado pelo sinal de “>” (maior).

Retornando ao texto no Sublime Text 3:
* A primeira linha do texto-base da página da Barbearia Alura é um título. Para ele, usaremos a tag “h”, de heading (cabeçalho em inglês). No primeiro título, utilizamos a tag ``` <h1>```.
* Em seguida ao título, temos o primeiro parágrafo do texto. Agora, a tag “p”, de paragraph (parágrafo em inglês), que será utilizada. Em cada parágrafo, empregamos a tag ``` <p>```.
* Sempre que uma tag é colocada seja para indicar o início de um título ou de um parágrafo, ela também deve ser inserida no final. É a mesma tag, mas começa com o símbolo “/”, por exemplo, ``` </h1>``` ou ``` </p>```.
Observe o exemplo a seguir:

```html
<h1> Sobre a Barbearia Alura </h1>
```

O texto da página Barbearia Alura no Sublime Text 3, com a aplicação das tags, deve ficar da seguinte maneira:

Ao salvarmos o texto-base da Barbearia Alura no Sublime Text 3 com as tags e recarregarmos a página no navegador, perceberemos que o texto da página da web está melhor estruturado. Agora, ele contém:
* Um título com fonte maior e em negrito;
* Divisão entre os parágrafos (conhecida por “quebra”).

Título com fonte maior e em negrito

“Quebra” entre os parágrafos

Os próximos passos que daremos são:
* Destacar o nome “Barbearia Alura”, colocando em negrito;
* Formatar o parágrafo “Nossa missão é: proporcionar autoestima e qualidade de vida aos clientes” em itálico.

Queremos colocar em itálico

Queremos colocar em negrito


Para formatar o texto em negrito no Sublime Text 3,
utilizamos a tag strong (“forte”, em inglês).

```html
<strong> Barbearia Alura </strong>
```

Para editar o texto com itálico no Sublime Text 3, usamos
a tag em.

```html
<p><em> Nossa missão é: “Proporcionar auto-estima e qualidade de vida aos clientes”. </em></p>
```

O texto-base da Barbearia Alura no Sublime Text 3 com as novas tags deverá ficar da seguinte forma:

Destaque em negrito para o nome “Barbearia Alura”.

Parágrafo em itálico.

Novamente, depois de salvarmos o texto-base da Barbearia Alura no Sublime Text 3, com as novas tags, e recarregarmos a página no navegador, iremos notar que o texto da página da web mostra um destaque no nome da barbearia e parágrafo em itálico:

Desafio

Pense em uma de página da web que você gostaria de desenvolver (pode ser sobre algum tipo de comércio, hobbie que te agrade ou um assunto de que você gosta). Elabore um pequeno texto de apresentação desta página.
Utilize os passos aprendidos nesta aula para criar e realizar as primeiras formatações do texto de apresentação da sua página.