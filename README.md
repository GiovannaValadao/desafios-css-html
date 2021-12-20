# desafios-css-html :rocket: 

## Objetivo

Melhorar as habilidades em CSS3/HTML através da realização de pequenos projetos.
## 🟢 Regras gerais :

- Cada projeto deverá ter o seu arquivo README contendo uma imagem/gif do resultado do desafio e uma pequena descrição do que foi aprendido no desafio.
- Os desafios não possuem layout fixo, aproveite para usar a criatividade e utilize o CSS para estilizar conforme preferir. Usar o [gerador de texto](https://www.lipsum.com/) para preencher as divs com textos.
- Em todos os desafios a página deve ficar responsiva para o mobile.

[## Desafio 1 -  Botão com efeito hover e Focus:](https://github.com/GiovannaValadao/desafios-css-html/tree/main/desafio-1)
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