# Jogo da Velha com React

Projeto para criação de um Jogo da Velha usando React.

## Visão Geral

O jogo foi feito baseado no [tutorial](https://pt-br.reactjs.org/tutorial/tutorial.html) disponível na própria documentação da linguagem. 
Durante o desenvolvimento há uma extensa explicação de diversos conceitos presentes na documentação do React. Estes não estão presentes neste README.md, mas podem ser encontrados no tutorial. 

Este README.md tem o objetivo de documentar o que já foi feito no projeto, bem como os próximos passos. Quaisquer dúvidas, críticas, dicas e elogios são bem vindos :)

## Passos já implementados

### Configuração de ambiente

O projeto foi realizado utilizando o Visual Studio Code.
As linguagens utilizadas foram React e Node.js, além disso, uma estrutura base foi baixada diretamente do [tutorial](https://pt-br.reactjs.org/tutorial/tutorial.html#setup-option-2-local-development-environment).

### Completando o jogo

Nesta etapa foi implementada toda a funcionalidade base de um Jogo da Velha. 
Por exemplo a construção do tabuleiro, configuração do jogo para marcar 'X' e 'O' em cada quadrado; a troca de turnos entre cada jogador; e a declaração de um vencedor de acordo com as regas do jogo.

### Adicionando a Viagem no Tempo

Nesta etapa foi adicionada a funcionalidade de armazenamento do histórico de jogadas dentro do programa. Possibilitando a visualização pelos jogadores das jogadas feitas, bem como a viabilidade de se voltar jogadas e reiniciar o jogo. 

## A fazer

As seguintes tarefas são recomendações do próprio tutorial, ainda a serem aplicadas no código: 

1) Mostrar a localização de cada jogada no formato (col,row), para cada jogada no histórico.
2) Estilizar com negrito o item da lista de jogadas que está selecionado no momento.
3) Reescrever o componente Board para utilizar 2 loops para fazer os quadrados, em vez de deixá-los hardcoded.
4) Adicionar um botão de toggle que lhe permita ordenar os jogadas em ordem ascendente ou descendente.
5) Quando alguém ganhar, destaque os 3 quadrados que causaram a vitória.
6) Quando ninguém ganhar, exiba uma mensagem informando que o resultado foi um empate.

