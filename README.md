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

- O que eu aprendi: 
A propriedade `transition` permite que você altere os valores das propriedades suavemente, como por exemplo altura ou largura, durante um determinado período.

Existem alguns tipos de `transition`, sendo eles:
  - `transition`: Uma propriedade abreviada para definir as quatro propriedades de transição em uma única propriedade
  - `transition-delay`: Especifica um atraso (em segundos) para o efeito de transição
  - `transition-duration`: Especifica quantos segundos ou milissegundos um efeito de transição leva para ser concluído
  - `transition-property`: Especifica o nome da propriedade CSS para a qual o efeito de transição se destina
  - `transition-timing-function`: Especifica a curva de velocidade do efeito de transição

No desafio também utilizei a propriedade `hover` para definir quando passar o cursor mouse sob o elemento ele se expanda e a propriedade `max-height`  para definir a altura máxima do elemento. 