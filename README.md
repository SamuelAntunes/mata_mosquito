# Jogo do Mosquito

Um jogo web responsivo e interativo onde o jogador deve clicar nos mosquitos que surgem aleatoriamente na tela para evitar perder vidas. O projeto possui vários modos de dificuldade, incluindo um modo "Infinito" onde não há limite de tempo, permitindo ao jogador acumular pontos enquanto a dificuldade aumenta progressivamente.

## Funcionalidades

- **Modos de Dificuldade:**  
  - **Normal:** Intervalo de criação padrão dos mosquitos.  
  - **Difícil:** Intervalo de criação mais rápido.  
  - **Chuck Norris:** Intervalo ainda mais rápido para um desafio extremo.  
  - **Infinito:** Modo sem limite de tempo, onde o jogador acumula pontos ao clicar nos mosquitos, e a dificuldade aumenta gradualmente.

- **Interface Responsiva:**  
  Layout adaptado para diferentes tamanhos de tela (desktops, tablets e smartphones).

- **Feedback Visual:**  
  Animação de aparecimento dos mosquitos e atualização dinâmica de cronômetro ou pontuação.

- **Gerenciamento de Vidas:**  
  O jogador inicia com 3 vidas e perde uma vida se não clicar no mosquito antes que um novo apareça.

## Tecnologias Utilizadas

- **HTML5:** Estrutura e marcação semântica.
- **CSS3:** Estilização, animações e media queries para responsividade.
- **JavaScript (ES6+):** Lógica do jogo utilizando recursos modernos como `let`, `const`, arrow functions e event listeners.

## Instalação e Execução

1. **Clone ou Baixe o Projeto:**  
   Faça o clone do repositório ou baixe os arquivos diretamente.

2. **Verifique as Imagens:**  
   Certifique-se de que todas as imagens necessárias estejam na pasta `imagens`. Entre as imagens utilizadas estão:  
   - `bg.jpg`
   - `game.png`
   - `coracao_cheio.png`
   - `coracao_vazio.png`
   - `mosquito.png`
   - `vitoria.png`
   - `game_over.png`
   - `mata_mosquito.png`

3. **Abra o Jogo:**  
   Abra o arquivo `index.html` em um navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge, etc.).

## Como Jogar

1. **Tela Inicial:**  
   Na tela de início, selecione o nível desejado (Normal, Difícil, Chuck Norris ou Infinito) e clique no botão "Iniciar Jogo".

2. **Durante o Jogo:**  
   - Nos modos com limite de tempo, um cronômetro exibido no painel conta regressivamente. O objetivo é clicar nos mosquitos para evitar a perda de vidas.
   - No modo Infinito, o cronômetro é substituído pela pontuação. Cada mosquito clicado aumenta a pontuação e, a cada 10 segundos, o intervalo de criação dos mosquitos diminui, aumentando a dificuldade.

3. **Fim de Jogo:**  
   - Se o jogador perder todas as vidas (ou o tempo acabar nos modos temporizados), a tela de "Game Over" é exibida.
   - Se o jogador completar o tempo limite com sucesso (nos modos com limite), a tela de "Vitória" é mostrada.

4. **Reiniciar:**  
   Clique no botão "Reiniciar" na tela de Vitória ou Game Over para voltar à tela inicial e iniciar uma nova partida.

## Estrutura do Projeto

- `index.html`:  
  Contém toda a estrutura do jogo (HTML, CSS e JavaScript) em um único arquivo, facilitando a execução e a manutenção.

- `imagens/`:  
  Pasta que contém os recursos visuais necessários para o jogo.

## Contribuições

Contribuições são muito bem-vindas! Se você deseja melhorar ou expandir o projeto, sinta-se à vontade para abrir issues ou pull requests.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).

---

Divirta-se jogando e sinta-se livre para contribuir com melhorias neste projeto!

