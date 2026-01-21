Sistema de IA para Navegação com Waypoints e Pathfinding (A*) 

Este projeto implementa um sistema de navegação utilizando waypoints conectados por um grafo,
permitindo que uma entidade se desloque entre diferentes pontos do cenário utilizando o algoritmo A*.

O foco do projeto é demonstrar lógica de sistemas, estrutura de dados e tomada de decisão,
independente de aspectos visuais ou artísticos.

Funcionalidades
- Estrutura de grafo para representação de caminhos
- Conexões unidirecionais e bidirecionais entre nós
- Cálculo de rotas utilizando o algoritmo A*
- Navegação automática entre waypoints
- Rotação suave e movimentação contínua até o destino
- Seleção dinâmica de destinos específicos

Estrutura do Sistema
- **WaypointManager**
  - Gerencia os nós (waypoints) e suas conexões
  - Constrói o grafo a partir das relações definidas
- **FollowWaypoints**
  - Controla a movimentação da entidade
  - Solicita caminhos ao grafo
  - Executa a navegação passo a passo até o destino

Tecnologias Utilizadas
- C#
- Unity (apenas como ambiente de execução)
- Algoritmo A*
- Estruturas de dados (grafos, listas, enums, structs)

Objetivo do Projeto
Projeto acadêmico desenvolvido com foco em:
- Lógica de programação
- Algoritmos de navegação
- Organização de código
- Sistemas baseados em regras e estados

> Obs: Este repositório contém apenas os scripts, com foco na lógica e arquitetura do sistema.
