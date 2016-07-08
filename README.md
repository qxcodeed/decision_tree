# Trabalho Árvore de Decisão #

Autor: Prof Fábio Dias
Adaptação: David Sena

## Descrição ##

O trabalho devem ser implementado em  C++ usando alocação dinâmica de
memória. 

A base do trabalho está explicada no vídeo: https://www.youtube.com/watch?v=cIiCsGfCN0A

Deve-se criar um ambiente de interface com o usuário via terminal que permita
uma boa interação entre usuário e o programa.

## Sistema de Auxilio no Processo de Decisão ##

Um programa de auxilio no processo de decisão tem por finalidade auxiliar a
tomada de decisão mediante a realização de algumas perguntas ao usuário do
programa. O programa irá fazer varias perguntas ao usuário com cada pergunta
contendo pelo menos duas respostas. Para cada resposta irá direcionar a uma nova
pergunta ou a uma decisão.
Por exemplo, digamos que você deseja saber onde jantar e o programa possui a
seguinte configuração:

![img1](figs/fig1.png?raw=true)

Se o usuário responder não a primeira pergunta e sim na segunda a decisão sugerida
ao usuário será “Santa Grelha”.
Veja outro exemplo abaixo:

![img1](figs/fig2.png?raw=true)

O trabalho é desenvolver este programa de auxilio no processo de decisão. Para
isso, deve-se usar uma estrutura de árvore n-ária. 
O programa terá as seguintes funcionalidades.

- Criação interativa da árvore de decisão: com capacidade para: inserir, remover, alterar nós.
- Cada pergunta terá pelo menos duas respostas.
- Ao sair do programa a árvore deverá ser serializada e salva em um arquivo de texto.
- Ao iniciar o programa a árvore deverá ser carregada do arquivo de texto.
- Modo de jogo onde o usuário vai fazendo as escolhas até chegar em uma decisão.
