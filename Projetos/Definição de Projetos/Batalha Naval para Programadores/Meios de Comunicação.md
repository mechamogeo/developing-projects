## REST API

Os jogadores podem fazer solicitações usando REST API para adivinhar a posição dos navios inimigos. No entanto, há um limite de duas solicitações por segundo para evitar que os jogadores enviem muitas solicitações em um curto período de tempo.

## WebRTC

Os jogadores também podem fazer solicitações usando WebRTC. Com o WebRTC, os jogadores podem enviar até três solicitações por segundo. No entanto, se eles enviarem mais de três solicitações por segundo, receberão uma penalidade de 250 ms para cada requisição adicional.

## GraphQL

Os jogadores também podem usar o GraphQL para fazer solicitações. No entanto, não há limitação de taxa para solicitações usando o GraphQL.

## Long Polling

Os jogadores podem usar o long polling para enviar solicitações e esperar por uma resposta. No entanto, o tempo limite para uma resposta é de 5 segundos.

## Short Polling

Os jogadores podem usar o short polling para enviar solicitações com mais frequência do que o long polling. No entanto, não há garantia de que a resposta chegará antes da próxima solicitação ser enviada.

## Detecção de Sobrevivência

Para garantir que os jogadores estejam sempre envolvidos no jogo, há um sistema de detecção de sobrevivência. Se um jogador não responder por 3 segundos, ele perde a vez de jogar. Se um jogador não responder por mais de 10 segundos, o time adversário será declarado vencedor.
