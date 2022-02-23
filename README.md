# desafios-css-html :rocket: 

## Objetivo

Melhorar as habilidades em CSS3/HTML através da realização de pequenos projetos.
## 🟢 Regras gerais :

- Cada projeto deverá ter no arquivo README contendo uma imagem/gif do resultado do desafio e uma pequena descrição do que foi aprendido no desafio.
- Os desafios não possuem layout fixo, aproveite para usar a criatividade e utilize o CSS para estilizar conforme preferir. Usar o [gerador de texto](https://www.lipsum.com/) para preencher as divs com textos.
- Em todos os desafios a página deve ficar responsiva para o mobile.

## [ Desafio 1 -  Botão com efeito hover e Focus:](https://github.com/GiovannaValadao/desafios-css-html/tree/main/desafio-1)
[![Image from Gyazo](https://i.gyazo.com/fbcd965e3d5bfa1d14b53de30275bf6e.gif)](https://gyazo.com/fbcd965e3d5bfa1d14b53de30275bf6e)

- O que eu aprendi:
  - A pseudo-class `:hover` é utilizada como efeito para alterar o estilo de um elemento(botões, imagens, links) quando o ponteiro do mouse estiver em cima. Existem outras pseudo-classes que podem serem utilizadas com o `:hover:`:
    -  `link`: Usado para selecionar os links dentro de um elemento.
    -  `visited`: Usado para indicar se o link em questão já foi visitado pelo usuário
    -  `active`: Usado para estilizar os links utilizamos o :active depois de todas as outras regras relacionadas ao link. 

         - Exemplo de um css do Elemento `<a>` com atributo `<href>`:
            `body { background-color: #ffffc9 }`
            `a:link { color: blue } /* links não visitados */`
            `a:visited { color: purple } /* links visitados */`
            `a:hover { font-weight: bold } /* user hovers */`
            `a:active { color: lime } /* links ativos */`

  - A pseudo-class `:focus` permite estilizar um elemento quando está em foco, o que pode ocorrer quando o usuário seleciona o elemento utilizando o teclado ou ativando o mesmo com o mouse.

A diferença entre `:hover` e `:focus` é:

- `:hover` quando o ponteiro do mouse está no elemento.

- `:focus` quando você seleciona um elemento, o elemento entra no foco.

## [ Desafio 2 -  Divs responsivas:](https://github.com/GiovannaValadao/desafios-css-html/tree/desafio-2/desafio-2)

<img width="1160" alt="Captura de Tela 2021-12-22 às 12 14 06" src="https://user-images.githubusercontent.com/42494406/147122244-4b548a21-175d-4500-b466-df60cc37b281.png">


- O que eu aprendi:

  - Flexbox: Torna o elemento um flex container automaticamente transformando todos os seus filhos diretos em flex itens.
  `align-items:`: O align-items alinha os flex itens de acordo com o eixo do container. O alinhamento é diferente para quando os itens estão em colunas ou linhas.

  `justify-content:`: Alinha os itens flex no container de acordo com a direção. A propriedade só funciona se os itens atuais não ocuparem todo o container.
  **Valores da propriedade:**
 - `justify-content: flex-start; // Alinha os itens ao início do container.`
- `justify-content: flex-end; // Alinha os itens ao final do container.`
- `justify-content: center; // Alinha os itens ao centro do container.`
- `justify-content: space-between; // Cria um espaçamento igual entre os elementos. Mantendo o primeiro grudado no início e o último no final.`
- `justify-content: space-around; // Cria um espaçamento entre os elementos. Os espaçamentos do meio são duas vezes maiores que o inicial e final.`

**Obs:** O flexbox alinha na horizontal usando o align-items e para a vertical o justify-content, isso porque por padrão ele considera os itens em linha. Mas se você utilizar o `flex-direction: column` essas funções invertem.

## [ Desafio 3 -   Div com conteúdo usando flex-box:](https://github.com/GiovannaValadao/desafios-css-html/tree/desafio-2/desafio-3)

- O que eu aprendi:

- Revisei alguns conceitos de flexbox, pois usei o `flex-start` que alinha os itens ao início do container.
Alem disso, usamos @media screen para criar um estilo diferente para quando for mobile. O @media é usado em consultas de mídia para aplicar estilos diferentes a tipos/dispositivos de mídia diferentes, pode ser usado para alterar estilo de largura, altura, resolução... 

Tipos de mídia:


Valor   | Descrição
--------- | ------
all | Padrão. Usado para todos os dispositivos de tipo de mídia
print	 | Usado para quando pedir imprimir a tela.
screen | Usado para telas de computador, tablets, smartphones etc.
speech	| Usado para leitores de tela que "lêem" a página em voz alta

- Desktop:
<img width="1661" alt="Captura de Tela 2021-12-27 às 11 30 59" src="https://user-images.githubusercontent.com/42494406/147481165-21099a94-4a0f-4b4d-963f-4f94782766ec.png">

- Mobile:
<img width="372" alt="Captura de Tela 2021-12-27 às 11 37 29" src="https://user-images.githubusercontent.com/42494406/147481689-8bb976c3-30a1-4502-b495-157f2f3537ba.png">

## [Desafio 4 - Expanda uma div ao passar o mouse](https://github.com/GiovannaValadao/desafios-css-html/tree/desafio-4/desafio-4)

![desafio4](https://user-images.githubusercontent.com/42494406/148235748-11acbdaa-4634-46ce-8914-ba08e550abdf.gif)


- O que eu aprendi: 
A propriedade `transition` permite que você altere os valores das propriedades suavemente, como por exemplo altura ou largura, durante um determinado período.

Existem alguns tipos de `transition`, sendo eles:
  - `transition`: Uma propriedade abreviada para definir as quatro propriedades de transição em uma única propriedade
  - `transition-delay`: Especifica um atraso (em segundos) para o efeito de transição
  - `transition-duration`: Especifica quantos segundos ou milissegundos um efeito de transição leva para ser concluído
  - `transition-property`: Especifica o nome da propriedade CSS para a qual o efeito de transição se destina
  - `transition-timing-function`: Especifica a curva de velocidade do efeito de transição

No desafio também utilizei a propriedade `hover` para definir quando passar o cursor mouse sob o elemento ele se expanda e a propriedade `max-height`  para definir a altura máxima do elemento. 

## [Desafio 5 - Lista de tarefas ](https://github.com/GiovannaValadao/desafios-css-html/tree/desafio-5/desafio-5)


- Desktop:

<img width="1345" alt="Captura de Tela 2022-01-10 às 01 36 51" src="https://user-images.githubusercontent.com/42494406/148719714-8eb0beaf-7da1-4611-b445-75e634a461d6.png">

- Mobile:

<img width="388" alt="Captura de Tela 2022-01-10 às 01 37 11" src="https://user-images.githubusercontent.com/42494406/148719700-e906ea2d-74e7-4c18-bd8f-cfad12f2786a.png">
- O que eu aprendi: 

   - Revisei conceitos de listas ordenadas para organizar as tarefas por ordem numérica
   - Usei o elemento `<input>` para criar os checks dos itens da lista com o type `checkbox` para criar uma caixa de marcação e o checked para indicar os itens selecionados por padrão.

   Além disso, o elemento `input` possui alguns outros tipos, sendo os principais:

type   | Descrição
--------- | ------
checkbox |  Uma caixa de marcação. Você deve usar o atributo value para definir o valor enviado por este item. Use o atributo checked para indicar se o item está selecionado por padrão. 
button | Um botão sem comportamento padrão.
color	 |Um controle para especificar cores. A interface de um seletor de cores não tem nenhuma funcionalidade obrigatória a não ser aceitar cores simples em texto 
date | Um controle para inserir uma data (ano, mês e dia, sem horário).
password	| Um campo de texto com uma só linha cujo valor é obscurecido. Use o atributo maxlength para especificar o comprimento máximo do valor que pode ser inserido.

## [Desafio 6 - Header com navegação ](https://github.com/GiovannaValadao/desafios-css-html/tree/desafio-6/desafio-6)

- O que eu aprendi: 

No desafio usei a tag `<header>` utilizada para criar o cabeçalho da página, é importante definir um header para estruturar a estrutura do documento e se uma pessoa com necessidades especiais usa um programa de acessibilidade para saber em que parte da página está sem enxergar, a tag div não oferece nenhuma informação para o programa. Mas a tag header deixa claro que ele esta no topo da página. Dentro da tag header utilizei a tag nav que é um elemento de Navegação `<nav>` que representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação. 
Obs: Nem todos os links de uma página HTML devem estar dentro de um elemento `<nav>`, o ideal é que ele seja usado para grupos importantes de links de navegação, como por exemplo o elemento `<footer>` que pode conter uma lista de links que não precisam estar em um elemento `<nav>`. E na tag nav criei listas para os tópicos da página

- Desktop:
<img width="1679" alt="Captura de Tela 2022-01-30 às 23 10 49" src="https://user-images.githubusercontent.com/42494406/151730176-9b52f552-d555-4c64-ac89-d40c17a7b6f2.png">

- Mobile:


<img width="377" alt="Captura de Tela 2022-01-30 às 23 11 16" src="https://user-images.githubusercontent.com/42494406/151730226-f365e0fb-0c06-440f-8990-994c7bd7d619.png">

## [Desafio 7 - Footer responsivo ](https://github.com/GiovannaValadao/desafios-css-html/tree/desafio-7/desafio-7)

- O que eu aprendi:

O elemento HTML de Rodapé `<footer>` representa um rodapé para o seu sectioning content (conteúdo de seção) mais próximo ou sectioning root elemento (ou seja, seu parente mais próximo `<article>`, `<nav>`, `<section>`,  `<body>`. Normalmente um rodapé contém informações sobre o autor da seção de dados, direitos autorais ou links para documentos relacionados.
Exemplo:
`<footer>`
  `Algumas informações de copyright ou talvez alguma informação do autor de um <article>`
`</footer>`
Para alinhar as colunas uma do lado da outra usei flexbox com `flex-direction:row` e a propriedade `gap` para o espaçamento entre as colunas.

Desktop:

<img width="1678" alt="Captura de Tela 2022-02-04 às 08 46 12" src="https://user-images.githubusercontent.com/42494406/152525403-f3218997-6441-47f5-b9d2-77c714d9d3d0.png">

Mobile:

<img width="377" alt="Captura de Tela 2022-02-04 às 08 46 03" src="https://user-images.githubusercontent.com/42494406/152525417-10d2df5f-7ee4-49a7-be75-5fa88bc7033a.png">

## [Desafio 8 - Formulário ](https://github.com/GiovannaValadao/desafios-css-html/tree/desafio-8/desafio-8)


Desktop:

<img width="1675" alt="Captura de Tela 2022-02-11 às 01 20 59" src="https://user-images.githubusercontent.com/42494406/153537131-d9b6539d-63c3-4d68-92bd-2a5da1695723.png">

Mobile:

<img width="367" alt="Captura de Tela 2022-02-11 às 01 19 10" src="https://user-images.githubusercontent.com/42494406/153537107-877375d6-b7cc-4599-b751-3cd7a59f6dfa.png">

- O que eu aprendi:


No desafio usei a tag form para criar o formulário na página, dentro do form usei o elemento `<input>` para criar inputs interativos para formulários para receber dados do usuário. O elemento possui a propriedade `type` que é O tipo de input a ser exibido e que possui alguns valores, como por exemplo:

type   | Descrição
--------- | ------
button: |   Um botão sem comportamento padrão.
checkbox: | Uma caixa de marcação. Você deve usar o atributo value para definir o valor enviado por este item. Use o atributo checked para indicar se o item está selecionado por padrão. Você também pode usar o atributo indeterminate para indicar que a caixa de marcação está em um estado indeterminado (na maioria das plataformas, isso desenha uma linha horizontal cortando a caixa).
datetime: | Um campo para inserir data e horário (hora, minuto, segundo e fração de segundo) baseado no fuso horário UTC.
email: |  Um campo para editar um endereço de e-mail. O valor do campo é validado para estar vazio ou ter um único endereço de e-mail válido antes de ser enviado. As pseudoclasses CSS :valid e :invalid são aplicadas apropriadamente.

Também utilizei o elemento `<label>` que representa uma legenda para um item em uma interface de usuário, nesse caso a legenda de cada input.

## [Desafio 9 - Tabela responsiva ](https://github.com/GiovannaValadao/desafios-css-html/tree/desafio-9/desafio-9)

Desktop:

<img width="1677" alt="Captura de Tela 2022-02-23 às 10 54 51" src="https://user-images.githubusercontent.com/42494406/155333153-758a5433-072e-4c7a-a75e-4ae82338a015.png">


Mobile:

<img width="409" alt="Captura de Tela 2022-02-23 às 10 54 30" src="https://user-images.githubusercontent.com/42494406/155333080-2f3dcb93-0e3f-48f1-825a-77825a0b4d34.png">

- O que eu aprendi:
  A tag `<table>`  define o começo e o fim da tabela dentro da página HTML. Dentro da tag <table> é possível criar cabeçalho, corpo, rodapé, linhas e colunas. 
  O objetivo da tag `<tr>` é definir as linhas da tabela, ela determina o fim e o começo de cada linha. Em uma tabela, cada `<tr>` contém dois tipos de células, sendo elas:
   - A tag `<th>` usada exatamente para criar e delimitar células de cabeçalho dentro de uma tabela, separando essas informações dos dados.
   - O outro tipo de célula é a de dados. Essa célula é definida pela tag `<td>`, assim delimitando onde começa e termina cada célula de dado presente nas linhas da tabela.
  No desafio também usei a propriedade CSS `:nth-child(` na tag `<tr>`. A propriedade recebe um único argumento que descreve um padrão para correspondência de índices de elementos em uma lista de irmãos. Os índices de elemento são baseados em 1. Existem dois valores que podem ser usados:

   valor   | Descrição
  --------- | ------
  odd: | Representa elementos cuja posição numérica em uma série de irmãos é ímpar: 1, 3, 5, etc.
  even: |Representa elementos cuja posição numérica em uma série de irmãos é par: 2, 4, 6, etc.

