# Jogo de Xadrez em Java :crown:

### Exemplo de execução
![Chess-system-image](https://github.com/LucasRafaell/chess-system-java/assets/99283985/0f4c93ff-de3c-416d-b18d-d7522c71b68d)

### Sobre o projeto
<div>
<p>Utilizando um planejamento desenhando todas as camadas do sistema em UML.</p>
  
<p>Camada Tabuleiro (Board layer) contendo as classes Board e Piece com relação de um tabuleiro para muitas peças. Possuindo também classes auxiliares BoardException para gerar exceções personalizadas e a classe Position que define a posição de uma peça no tabuleiro.</p>

<p>Camada Xadrez (Chess) contendo regras de passagem de turno, identificação de peças por cor, lógica de movimentação da peças, lógica de check e checkMate. Possuindo as classes ChessMatch que contém propriedades e operações que podem ser executadas que contém um Board causando uma dependência da camada tabuleiro. É contida também na cama Chess a classe ChessPiece herdada da classe Piece da camada Tabuleiro com mais propriedades que sua classe mãe, sendo ambas abstratas, pois as classe concretas serão as peças especificas do xadrez, sendo elas: King, Bishop, Knight, Pawn, Queen e Rook. Ainda na camada Xadrez temos algumas classes auxiliares sendo elas ChessPosition, Color e ChessException.</p>

<p>Utilizando o prompt de comandos para executar o sistema é possível identificar o tabuleiro em formato de matriz com as peças posicionadas e mais a baixo informações relevantes para o jogo, como peças capturadas e jogador da vez.</p>

<p>Para movimentar uma peça o jogador da vez deve selecionar a peça desejada através do posicionamento da mesma identificado por linha e coluna, onde as linhas são números e as colunas são letras. Ao inserir uma coluna e uma linha a peça será selecionada e será possível identificar as possíveis jogadas pelos campos coloridos no tabuleiro.</p>

<p>As peças assim como as colunas também são identificas por letras, no caso das peças as letras estão em caixa alta, podemos identificas as peças pelas seguintes letras:
P: peão; R: torre; N: cavalo; B: bispo; Q: rainha e K: rei.</p>

<p>Obs: pelo fato do background do prompt de comandos ser pretos as peças pretas precisaram ser identificadas com a cor amarela, para que fosse possível visualiza-las.</p>

<p>O sistema é preparado para tratar todas as exceções possíveis, indicando a mensagem correta para cada caso.</p>
</div>

### Tecnologias utilizadas
<div align="left"> 
  <img height="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-plain.svg" title="Java">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img height="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" title="Git">
</div>

## Como executar a aplicação

### Pré-requisitos:

Java 17, Git Bash ou SO Linux.

### Comandos Git para execução:

1º Passo: Abrir o Git Bash e clonar o repositório:

```bash
git clone https://github.com/LucasRafaell/chess-system-java
```

2º Passo: Entrar na pasta bin do projeto, iniciar o git bash e em seguida aplicar:

```bash
java application/Program
```

## Autor
<p>Lucas Rafael</p>
<section align="left">  
  <div> 
    <a href = "mailto:lucasrafaelinfo@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank" title="E-mail: lucasrafaelinfo@gmail.com"></a>
      &nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/lucas-rafael-dev/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" title="Linkedin: Lucas Rafael"></a>
  </div>
</section>
