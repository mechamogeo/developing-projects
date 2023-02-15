![Cover](Definição%20de%20Projetos/Batalha%20Naval%20para%20Programadores/cover.png)

## Descrição do Jogo

Batalha Naval para Programadores é um jogo de estratégia baseado no clássico jogo de tabuleiro Batalha Naval. O jogo é projetado para testar as habilidades dos programadores em várias áreas, como desenvolvimento de API, criptografia e comunicação em rede.

## Objetivo do Jogo

O objetivo do jogo é afundar todos os navios do time adversário antes que eles afundem os seus. As equipes escolhem a posição dos seus navios em um tabuleiro e então usam diferentes meios de comunicação para adivinhar a posição dos navios do time adversário e atacá-los.

## Regras Básicas

- Cada equipe tem um tabuleiro de 10x10 para posicionar seus navios.
- As equipes devem escolher a posição dos seus navios antes de começar o jogo.
- Cada equipe pode atacar uma posição do tabuleiro do time adversário a cada rodada.
- Se o ataque acertar um navio do time adversário, a equipe atacante recebe um ponto.
- O jogo termina quando todos os navios de um time forem afundados.

----

## [Funcionalidades Básicas](Definição%20de%20Projetos/Batalha%20Naval%20para%20Programadores/Funcionalidades%20Básicas.md)

- Os jogadores devem ser divididos em dois times
- Um meio de escolha de time deve ser criado
- Os jogadores devem se comunicar por meio de rest api, webrtc, graphql, long pooling ou short pooling
- Os jogadores devem ser capazes de atacar o time adversário
- O sistema deve manter o controle dos pontos de cada jogador
- O sistema deve aplicar penalidades aos jogadores que violarem as regras
- O jogo deve terminar quando um dos times destruir todos os navios do time adversário
- O sistema deve manter o controle das estatísticas do jogo

## [Gamificação](Definição%20de%20Projetos/Batalha%20Naval%20para%20Programadores/Gamificação.md)

- Os jogadores ganham pontos por realizar ações específicas, como usar rest api ou criptografia
- Os jogadores são penalizados por violar as regras, como exceder o limite de requisições por segundo ou não enviar uma mensagem Ping dentro do tempo limite
- O jogo deve ser divertido e envolvente para incentivar os jogadores a continuarem jogando

## [Meios de Comunicação](Definição%20de%20Projetos/Batalha%20Naval%20para%20Programadores/Meios%20de%20Comunicação.md)

- Os jogadores devem se comunicar por meio de rest api, webrtc, graphql, long pooling ou short pooling
- Cada meio de comunicação tem suas próprias regras e limitações

## [Detecção de Sobrevivência](Definição%20de%20Projetos/Batalha%20Naval%20para%20Programadores/Detecção%20de%20Sobrevivência.md)

- O sistema deve enviar mensagens Ping para garantir que os jogadores estejam online e respondendo
- Se um jogador não responder às mensagens Ping por 3 segundos, a vez passa para o outro time
- Se um jogador não responder às mensagens Ping por 10 segundos, o time adversário ganha a partida

## [Consultas](Definição%20de%20Projetos/Batalha%20Naval%20para%20Programadores/Consultas.md)

- Os jogadores devem ser capazes de consultar seus pontos, penalidades e as regras do jogo

## [Requisitos Não Funcionais](Definição%20de%20Projetos/Batalha%20Naval%20para%20Programadores/Requisitos%20Não%20Funcionais.md)

- O jogo deve ser escalável para suportar um grande número de jogadores
- O jogo deve ser seguro e protegido contra ataques
- O jogo deve ser fácil de usar e intuitivo para os jogadores
- O jogo deve ser rápido e responsivo, sem atrasos ou problemas de latência
- O jogo deve ser compatível com diferentes dispositivos e navegadores
- O jogo deve ser capaz de lidar com diferentes tipos de conexão de internet, incluindo conexões lentas ou intermitentes
- O jogo deve ser capaz de lidar com diferentes tipos de jogadores, incluindo programadores iniciantes e avançados
- O jogo deve ser capaz de lidar com diferentes tipos de dispositivos, incluindo computadores, smartphones e tablets
