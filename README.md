♟️ Sistema de Xadrez em Camadas (Java)
Este projeto consiste no desenvolvimento de um sistema completo de xadrez, estruturado em camadas e implementado com os princípios da Programação Orientada a Objetos (POO). O objetivo é simular partidas entre dois jogadores, seguindo as regras oficiais do jogo e aplicando boas práticas de engenharia de software. Feito pelos alunos Filipe Coelho e Maria Eduarda Negreiro.


🎯 Objetivo
Criar uma aplicação capaz de:
  Gerenciar uma partida de xadrez entre dois jogadores.
  Executar movimentos válidos de acordo com as regras oficiais.
  Verificar situações de xeque e xeque-mate.
Realizar movimentos especiais:
    Roque
    Promoção
    En passant  
  Realizar operações de captura e controle de turno.
  Oferecer uma interface simples via console para interação do usuário.

🧱 Arquitetura em Camadas
O sistema segue uma divisão clara em duas camadas principais:
1. Board Layer (Camada do Tabuleiro)
Responsável por:
  Controlar o tabuleiro.
  Gerenciar posições válidas.
  Colocar e remover peças.
  Representar o estado da partida usando uma matriz.

2. Chess Layer (Camada de Xadrez)
Responsável pelas regras e lógica do jogo:
  Movimentação das peças.
  Identificação de movimentos permitidos.
  Controle de turnos e cores.
  Lógica de xeque e xeque-mate.
  Implementação de exceções específicas do xadrez.

🧩 Estrutura do Projeto
O projeto utiliza conceitos fundamentais de POO:
  Encapsulamento: separação clara entre responsabilidades.
  Herança: classes específicas de peças especializadas a partir de uma classe base.
  Polimorfismo: comportamento distinto por tipo de peça.
  Associações e Enumerações: vínculo entre peças, posições e cores.
  Exceções personalizadas: para regras inválidas de movimento.

Principais componentes:
  Board
  Position
  Piece
  ChessPiece e subclasses (Rei, Rainha, Torre, Bispo, Cavalo, Peão)
  ChessMatch (controle da partida)
  ChessException
  Interface via console (renderização do tabuleiro e comandos do usuário)

🛠️ Tecnologias Utilizadas
  Java
  Matriz bidimensional para representação do tabuleiro
  Git e GitHub para controle de versão
  UML para modelagem da arquitetura

🧪 Desenvolvimento e Testes
A implementação foi feita de forma incremental, incluindo testes após cada etapa:
  Criação e renderização do tabuleiro
  Colocação e movimentação das peças
  Regras de captura
  Movimentos especiais
  Detecção de xeque e xeque-mate

📄 Entregáveis
  Código-fonte completo organizado em camadas.
  Documentação das classes e principais métodos.
  Diagrama UML representando a arquitetura.
  Relatório de decisões de projeto e regras implementadas.
  Vídeo de apresentação demonstrando o funcionamento do sistema.

🎥 Vídeo de Apresentação
O vídeo apresenta:
  Os membros da dupla
  A arquitetura do sistema
  Demonstração dos principais recursos e regras implementadas
  Desafios enfrentados no desenvolvimento
