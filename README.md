## Descrição

Plataforma de Lives

Microsserviço de transmissão de lives

# Tecnologias e ferramentas
- Node (Nest.js)
- React (MUI)
- Typescript
- Go Lang
- gRPC (Google Remote Procedure Call / HTTP2)
- Websockets (Pub / Sub)
- WebRTC (Client <-> Client / Real Time communication for the web)
    - Peer.js
        - STUN Server (Session Transversal Utilities for NAT)
        - TURN Server (Transversal using Relay for NAT)
- RabbitMQ (Queues / Fan out)
- Istio
- Kiali
- MySQL
- Postgres
- Redis

## Rodar a aplicação

#### Antes de começar

- Dê permissão a+x para o ./docker/entrypoint.sh

- Demora um pouco para levantar os microserviços as vezes.

A aplicação foi construída utilizando os conceitos de microsserviços e arquitetada com Docker. 

Para roda-la será necessário basicamente rodar o comando **docker-compose up --build**.

Acesse cada microsserviço respectivamente e leia o README.md para ver mais detalhes de como rodar o microsserviço.

- Live-Manager
- CodeBot
- Live-Chat
- Live-Streaming

#### Para quem usar Docker Professional no Windows

As versões maiores que 2.2 estão apresentando problemas com compartilhamento de volumes, notificações de modificações entre
o container e a máquina, entre outros problemas.

Portanto, não recomendamos usar estas versões no momento, use a 2.1.0.5, baixe-a neste [link](https://t.co/wK5Ai3fTfn?amp=1).
