# repertorio do jogo e analise 

A analise de requisitos é bom para clariar a visão de roteiro e para o a direção do projeto, ajuda a garanti que o software seja capaz de atingir o objetivo  

# 6 etapas principais para os requisitos de analise 

Etapa 1 - indentificar as partes interesadas do projeto como gerente, cliente e até mesmo a propria equipe, por mais que seja inetresses diferentes conta do mesmo jeito
caso a desenvolvidor preferir agrupar em notas ou anotar os diferentes intereses de cada um é masi facil para se organizar na criação do jogo  

etapa 2 - 

# tecnica utilizada User Storie (descrição curta e informal)

Como jogador, quero que o sistema escolha um número secreto automaticamente, para que eu possa tentar adivinhar.
Como jogador, quero digitar um número como palpite, para tentar adivinhar o número secreto.
Como jogador, quero receber uma mensagem se o palpite está correto, maior ou menor, para saber se continuo tentando.
Como jogador, quero que o jogo conte quantas tentativas eu fiz, para eu saber meu desempenho.
Como jogador, quero que o jogo termine quando eu acertar o número, para encerrar a partida.

# Requisitos Não Funcionais

O jogo deve ser simples e rápido de usar.
Deve rodar em qualquer computador com Python ou navegador (se for em JavaScript).
O sistema deve responder imediatamente a cada tentativa.

# Fluxo do Jogo

O sistema gera aleatoriamente um número secreto.
O jogador digita um palpite.
O sistema verifica o palpite:
Se for maior → mostra “Tente um número menor”.
Se for menor → mostra “Tente um número maior”.
Se for igual → mostra “Parabéns, você acertou em X tentativas!”.
O jogo termina quando o jogador acerta.

# Caso de Uso (UML)

Mesmo que a técnica principal seja User Stories, você pode reforçar mostrando o diagrama.

Ator principal: Jogador
Sistema: Jogo de Adivinhação

# Caso de Uso:

Jogar partida
Inserir palpite
Receber dica (maior/menor)
Acertar número secreto
