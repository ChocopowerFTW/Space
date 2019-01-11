# Welcome to StackEdit!

Hi! I'm your first Markdown file in **StackEdit**. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the **file explorer** on the left corner of the navigation bar.



![CAPITAL CODE-LOGO](https://i.imgur.com/v1gbp9c.jpg)

# [Capital Code](https://capitalcode.com.br)- Space Capital, conheça os planetas de uma forma diferente! #

  
  

![VERSÃO DO SW](https://img.shields.io/badge/Spacel%20Capital--%20version-v.1.1.7-blue.svg)

![Elf](https://img.shields.io/badge/Guardian-01-blue.svg)

O **Space Capital** é uma nova forma de interagir com os planetas, com um simples toque na superfície do planeta você consegue ver a sua distância em km até o sol.

O Space Capital foi feito totalmente com Javascript e Jquery, apresentando assim o mais alto desempenho no Front-end.

## Interação com o usuário

O evento do clique, aciona a função que seta as informações sobre o planeta:

<div class="planet p-1" onclick="setDistancia('90')">

## Número com animação

Ao clicar no botão, a função "setDistancia" é chamada e uma animação do contador é realizada dessa forma:

function setDistancia($distancia){

  

$('#distancia').animateNumber({ number: $distancia })

  

}

## Plugin para contador

- [jquery-animateNumber](https://github.com/aishek/jquery-animateNumber)

  

Para mais informações acesse [a nossa plataforma](https://capitalcode.com.br).[enter link description here](https://capitalcode.com.br)