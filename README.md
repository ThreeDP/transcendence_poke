
<p align="center">
    <img height="200" width="200" src="https://github.com/user-attachments/assets/8730e9b3-821e-4be7-82d5-de197e97d857" />
</p>

# Transcendence Poke
O projeto "Pong Game Multiplayer via Browser" é uma implementação moderna do clássico jogo Pong, adaptado para um ambiente multiplayer na web. Utilizando Python com Django para o backend e JavaScript para o frontend, o jogo permite que os jogadores joguem em tempo real através de seus navegadores em PCs. Além de permitir partidas multiplayer, o jogo também oferece a possibilidade de desafiar uma inteligência artificial (IA) e organizar torneios entre múltiplos jogadores. O sistema é construído com uma arquitetura de microserviços para melhorar a escalabilidade e a manutenção.

## Objetivos
- Criar um jogo Pong multiplayer acessível via navegador web em PCs: Permitir que dois jogadores participem do jogo simultaneamente através de seus navegadores em PCs.
- Implementar uma interface intuitiva e responsiva: Garantir que o jogo seja fácil de jogar e visualmente agradável em diferentes tamanhos de tela de PCs.
- Desenvolver uma solução de comunicação em tempo real: Utilizar WebSockets ou outra tecnologia adequada para garantir uma sincronização eficiente e baixa latência entre o backend e os clientes.
Implementar uma IA desafiadora: Permitir que os jogadores desafiem uma inteligência artificial em partidas individuais.
- Desenvolver um sistema de torneios: Facilitar a organização de torneios entre múltiplos jogadores, possibilitando uma experiência de competição mais estruturada.
Utilizar uma arquitetura de microserviços: Dividir o sistema em serviços menores e independentes para melhorar a escalabilidade e a manutenção, como serviços para gerenciamento de jogos, controle de torneios e interação com a IA.
- Fornecer um código limpo e documentado: Facilitar a compreensão e a manutenção do projeto, além de permitir que outros desenvolvedores contribuam e personalizem o jogo conforme necessário.

## Justificativa
O Pong é um dos primeiros jogos icônicos e uma referência importante na história dos jogos. Atualizá-lo para um formato multiplayer via navegador é uma forma de homenagear este clássico enquanto explora as capacidades modernas da web. A implementação com Python e Django para o backend e JavaScript para o frontend oferece uma solução robusta para comunicação em tempo real e interatividade. A inclusão de uma IA e a possibilidade de torneios tornam o jogo mais envolvente e diversificado, proporcionando uma experiência de jogo rica e desafiadora que pode ser compartilhada e jogada com amigos em PCs. A adoção de uma arquitetura de microserviços permitirá uma maior flexibilidade e eficiência na gestão dos diferentes componentes do sistema.

## Problema
A principal dificuldade neste projeto é garantir uma experiência de jogo fluida e sincronizada para todos os jogadores, considerando que a comunicação entre clientes e o backend deve ser realizada em tempo real. Isso envolve resolver desafios como:

- Latência e sincronização: Garantir que os movimentos dos jogadores, a bola e a IA sejam atualizados em tempo real e que todos os jogadores vejam o mesmo estado do jogo simultaneamente.
- Gerenciamento de conexões: Lidar com possíveis desconexões e reconexões, bem como manter a integridade do jogo durante essas interrupções.
- Desempenho e escalabilidade: Otimizar o código para que o jogo funcione bem em uma ampla gama de PCs e garantir que o servidor suporte múltiplas partidas e torneios simultaneamente sem perda de desempenho.
- Desenvolvimento da IA: Criar uma inteligência artificial que ofereça um desafio adequado e uma experiência de jogo equilibrada para os jogadores.
- Coordenação dos microserviços: Garantir que todos os microserviços trabalhem juntos de forma coesa e que a comunicação entre eles seja eficiente e confiável.
