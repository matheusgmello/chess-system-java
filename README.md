# Chess System Java
<a href="https://imgur.com/yOIuduF"><img src="https://i.imgur.com/yOIuduF.png" title="source: imgur.com" /></a>

Este projeto é um jogo de xadrez desenvolvido em Java como parte de um estudo sobre programação orientada a objetos. O objetivo é simular um jogo de xadrez completo, com todas as regras e movimentos válidos.

## Funcionalidades

- Movimentos válidos para cada peça, incluindo roque, en passant e promoção de peões;
- Detecção de xeque, xeque-mate e empate;
- Possibilidade de desfazer jogadas e reiniciar a partida;
- Visualização do tabuleiro em modo texto no console.

## Tecnologias

- Java 8
- Maven
- JUnit5

## Como executar o projeto

1. Clone o repositório: git clone https://github.com/matheusgmello/chess-system-java.git
2. Acesse a pasta do projeto: cd chess-system-java
3. Compile o projeto com o Maven: mvn package
4. Execute o arquivo JAR gerado na pasta target: java -jar target/chess-system-java.jar

## Como jogar

Para jogar, basta executar a classe Program na pasta src/application. O jogo irá iniciar e pedir o nome dos jogadores. Em seguida, basta informar as coordenadas de origem e destino da peça que deseja mover. Por exemplo, para mover o peão da casa e2 para e4, o jogador deve digitar "e2 e4".

Ao longo da partida, o sistema irá informar se uma jogada é inválida ou se resulta em xeque ou xeque-mate. Também é possível desfazer jogadas usando o comando "undo".

- Para realizar um movimento, digite a posição da peça que deseja mover e a posição para onde deseja movê-la, separados por um espaço. Por exemplo: a2 a4.
- Para desfazer um movimento, digite undo.
- Para reiniciar a partida, digite reset.

## Agradecimentos
   Projeto criado baseado nas aulas do professor Nelio Alves do DevSuperior
