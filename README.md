# Jogo da Velha - README

Este projeto é um jogo da velha (tic-tac-toe) interativo desenvolvido com HTML, CSS e JavaScript. O jogo suporta dois jogadores (Player X e Player O) e mantém um placar de vitórias e empates. Além disso, permite reiniciar o jogo e resetar o placar.

## Funcionalidades

- **Dois jogadores:** Um jogador usa o símbolo "X" e o outro "O".
- **Detecção de vitórias e empates:** O jogo verifica automaticamente quando um jogador vence ou se há um empate.
- **Contador de vitórias:** Mantém a contagem de vitórias para cada jogador.
- **Contador de empates:** Mantém a contagem de empates.
- **Botão de reiniciar o jogo:** Reinicia a partida atual sem alterar o placar.
- **Botão de resetar o placar:** Reseta o placar de vitórias e empates.

## Estrutura de Código

### HTML

- O arquivo HTML contém a estrutura básica do jogo, incluindo:
  - O cabeçalho e o título do jogo.
  - O tabuleiro de jogo com 9 células.
  - Elementos para exibir a contagem de vitórias e empates.
  - Mensagens de vitória e botões para reiniciar e resetar o jogo.

### CSS

- O estilo do jogo é gerido por um arquivo CSS externo (`style.css`), responsável por:
  - A aparência do tabuleiro.
  - A formatação das células e do layout.
  - Efeitos de hover para indicar a vez do jogador.
  - Estilização da mensagem de vitória e botões de interação.

### JavaScript

O arquivo de script (`scripts.js`) contém toda a lógica do jogo:

#### Elementos Selecionados:

- **Células do tabuleiro:** Seleciona todas as células que representam o jogo da velha.
- **Container do tabuleiro:** Seleciona o container que agrupa o tabuleiro.
- **Mensagem de vitória:** Seleciona o elemento onde será exibida a mensagem de vitória ou empate.
- **Botões:** 
  - O botão para reiniciar a partida atual.
  - O botão para resetar o placar de vitórias e empates.

#### Variáveis de Contagem:

- **countX:** Variável que mantém a contagem de vitórias do Player X.
- **countO:** Variável que mantém a contagem de vitórias do Player O.
- **countDraws:** Variável que mantém a contagem de empates.

#### Lógica de Jogo:

1. **Iniciar o jogo (`startGame`):**
   - Define quem começa jogando.
   - Limpa o tabuleiro e adiciona eventos de clique para cada célula.
   - Remove a mensagem de vitória.

2. **Fim do jogo (`endGame`):**
   - Exibe uma mensagem de vitória ou empate, dependendo do resultado da partida.

3. **Incrementar vitórias e empates:**
   - Atualiza as contagens de vitórias dos jogadores e a contagem de empates.

4. **Verificar vitória (`checkForWin`):**
   - Verifica se as combinações vencedoras estão preenchidas pelo mesmo jogador.

5. **Verificar empate (`checkForDraw`):**
   - Verifica se todas as células estão preenchidas sem que haja um vencedor.

6. **Alternar turnos (`swapTurns`):**
   - Alterna entre os jogadores após cada jogada.

7. **Colocar marca (`placeMark`):**
   - Adiciona a marca correspondente (X ou O) à célula clicada.

8. **Resete do placar (`buttonReset`):**
   - Reseta as contagens de vitórias e empates.

## Como Executar

## Clone este repositório para o seu computador.
   ```bash
   git clone https://github.com/SEU_USUARIO/jogo-da-velha.git
   ```
    Abra o arquivo index.html em um navegador.

    Jogue o jogo da velha com dois jogadores!
  
## Como Jogar

    - O jogo começa com o jogador "X".
    - Clique em uma célula vazia para marcar sua jogada.
    - O jogo alterna automaticamente para o próximo jogador após cada jogada.
    - O jogo detecta automaticamente quando há um vencedor ou empate.
    - Ao final da partida, uma mensagem exibirá o resultado.
    - Use o botão "Reiniciar" para jogar novamente sem alterar o placar ou o botão "Zerar" para resetar as pontuações.

## Tecnologias Utilizadas

   - HTML5
   - CSS3
   - JavaScript

## Autor

Desenvolvido por Diogo Henrique.

GitHub: DHstation
