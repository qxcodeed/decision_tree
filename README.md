# Trabalho Árvore de Decisão #

Autor: Prof Fábio Dias

## Descrição ##

O trabalho devem ser implementado em C ou C++ usando alocação dinâmica de
memória. Não será cobrada interface gráfica, mas quem fizer ganhará ponto extra.
Deve-se criar um ambiente de interface com o usuário via terminal que permita
uma boa interação entre usuário e o programa.
Cada equipe deverá entregar o código fonte e deverá apresentar para o professor
explicando os detalhes da implementação e onde o professor irá realizar perguntas
sobre o código.

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
isso, deve-se usar pelo menos árvore e fila.
O programa terá as seguintes funcionalidades.

- Cada pergunta terá pelo menos duas respostas.
- Cadastro da árvore de perguntas completa. Primeiro solicita a pergunta raiz,
para cada resposta solicita ao usuário se a resposta será uma decisão ou uma
nova pergunta. O caminho que o programa irá fazer para solicitar as
respostas será o caminho feito na busca em largura.
- Alterar a árvore de perguntas. O programa irá pergunta onde deseja incluir
uma nova pergunta. Para isso o programa irá exibir as perguntas, iniciando
na raiz e solicitando a resposta do usuário e após cada resposta o programa
irá perguntar se deseja incluir neste vértice ou continuar. Quando o usuário
decidir incluir naquele vértice, o programa solicitar a nova pergunta e a
subárvore cuja raiz era o vértice atual será a subárvore de uma resposta da
nova pergunta que o usuário irá informar. Depois o programa irá retorna o
cadastro de novas perguntas para os demais vértices, se houver, ou apenas
cadastrar uma decisão. Veja exemplo abaixo:

Antes

![](figs/fig3a.png?raw=true)

Durante

![](figs/fig3b.png?raw=true)

Depois

![](figs/fig3c.png?raw=true)

- Salvar as perguntas em arquivo. Será realizado no momento que o usuário
clicar em sair do programa. O formato está livre, vocês decidem.
- Leitura de arquivos com todas as perguntas e decisões ao iniciar o programa.
- Verificar se cada folha possui uma decisão, ou seja, se a árvore de decisão
está consistente.
- Iniciar questionário. O programa irá exibir a pergunta na primeira linha e na
segunda as respostas com um número entre parênteses para cada resposta.
Esse número será a forma que o usuário irá usar para responder. Na terceira
linha será a entrada da resposta pelo usuário.
- Sair. Liberar todas as memórias e finalizar o programa.