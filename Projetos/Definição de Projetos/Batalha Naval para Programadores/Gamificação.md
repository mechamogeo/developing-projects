## Sistema de Pontuação

O jogo usa um sistema de pontos para incentivar o uso de diferentes tecnologias e práticas de programação. A cada vez que um jogador faz uma jogada usando uma tecnologia específica, ele ganha pontos correspondentes. O sistema de pontuação atual inclui:

- 1 ponto para cada requisição feita usando REST API
- 2 pontos para cada requisição criptografada
- 1 ponto extra para cada requisição feita em menos de 2 segundos

## Limitações de Requisição

Para evitar um jogo desigual, há limites de taxa para as solicitações de API. Cada jogador só pode fazer no máximo duas requisições por segundo usando REST API. No entanto, os jogadores podem enviar até três requisições por segundo usando a conexão WebRTC. Se eles enviarem mais de três solicitações por segundo, eles receberão uma penalidade de 250 ms para cada requisição adicional.

## Consulta de Penalidades

Os jogadores podem verificar suas penalidades a qualquer momento durante o jogo, por meio de um meio de consulta fornecido.

