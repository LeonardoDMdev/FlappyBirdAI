Este projeto é uma implementação do jogo Flappy Bird utilizando Python e Pygame, com uma inteligência artificial treinada usando a biblioteca NEAT-Python para "zerar" o jogo.
Como funciona?
O algoritmo NEAT (NeuroEvolution of Augmenting Topologies) é utilizado para treinar uma população de redes neurais artificiais, permitindo que os pássaros aprendam a jogar sozinhos. Com o tempo, eles evoluem, melhorando suas decisões e reflexos para superar os obstáculos.
A IA cria 100 pássaros por geração. Se a primeira geração morrer, serão selecionados os 2 melhores pássaros e criados mais 98 com base nos 2 melhores da primeira geração, mas com mínimas diferenças. Assim, a IA pode ir se aprimorando.

Tecnologias utilizadas:
Python → Linguagem principal do projeto.
Pygame → Para renderizar o jogo e gerenciar eventos.
NEAT-Python → Para treinar a IA através de evolução neural.

