### README

# Mini-Game: Sequência de Teclas

## Apresentação

Olá! Meu nome é Christian Dambock Gomes e sou desenvolvedor front-end com experiência em criação de aplicações interativas e dinâmicas utilizando React. Este projeto é um mini-game desenvolvido como parte de um desafio de front-end. O objetivo do jogo é testar a habilidade do jogador em seguir rapidamente uma sequência aleatória de teclas dentro de um tempo limite.

## Sobre o Jogo

### Descrição

Neste mini-game, o jogador deve seguir uma sequência de teclas que aparece na tela, pressionando cada tecla na ordem correta. O jogo é uma excelente maneira de treinar a memória e a agilidade, proporcionando diversão e desafio para todos os jogadores.

### Lógica do Jogo

1. **Início do Jogo**: Ao iniciar o jogo, uma sequência aleatória de letras de A a Z é gerada e exibida ao jogador.
2. **Objetivo**: O jogador deve pressionar as teclas na ordem correta dentro do tempo limite.
3. **Feedback Visual**: 
   - A próxima tecla a ser pressionada é destacada em amarelo.
   - Se a tecla pressionada estiver correta, ela ficará verde.
   - Se a tecla pressionada estiver incorreta, ela ficará vermelha e o jogo terminará.
4. **Fim do Jogo**: O jogo termina se o jogador pressionar a tecla errada ou se o tempo acabar. O jogador será notificado e poderá ver sua pontuação.
5. **Reinício**: O jogador pode reiniciar o jogo a qualquer momento para começar do zero.

### Recursos Adicionais

- **Ranking Local**: O jogo armazena e exibe as melhores pontuações localmente, permitindo que o jogador veja seu progresso ao longo do tempo.
- **Animações e Feedback Auditivo**: Animações visuais tornam o jogo mais atraente, enquanto sons de feedback (correto e incorreto) melhoram a experiência do jogador.

### Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **Styled-components**: Biblioteca para estilização de componentes em React.
- **React-spring**: Biblioteca para animações em React.

## Instruções para Executar o Jogo

### Pré-requisitos

- Node.js instalado
- NPM ou Yarn instalado

### Passos para Execução

1. **Clonar o Repositório**

   ```sh
   git clone https://github.com/seu-usuario/minigame-sequencia-teclas.git
   cd minigame-sequencia-teclas
   ```

2. **Instalar Dependências**

   ```sh
   npm install
   ```

   ou

   ```sh
   yarn install
   ```

3. **Iniciar o Jogo**

   ```sh
   npm start
   ```

   ou

   ```sh
   yarn start
   ```

   O jogo estará disponível em `http://localhost:3000`.

### Estrutura do Projeto

```plaintext
minigame/
│
├── public/
│   ├── correct.mp3
│   ├── incorrect.mp3
│   ├── index.html
│   └── ...
│
├── src/
│   ├── components/
│   │   ├── GameScreen/
│   │   │   ├── GameScreen.jsx
│   │   │   ├── GameScreenController.js
│   │   │   ├── GameScreenStyles.js
│   │   ├── StartScreen/
│   │   │   ├── StartScreen.jsx
│   │   │   ├── StartScreenStyles.js
│   │   ├── Ranking/
│   │   │   ├── Ranking.jsx
│   │   │   ├── RankingStyles.js
│   ├── App.jsx
│   ├── App.css
│   └── index.js
└── ...
```

## Contribuição

Se você encontrar algum problema ou tiver alguma sugestão para melhorar o jogo, sinta-se à vontade para abrir uma issue ou enviar um pull request no repositório do GitHub.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Espero que você se divirta jogando este mini-game tanto quanto eu me diverti desenvolvendo-o! Se tiver alguma dúvida ou feedback, não hesite em entrar em contato.

Christian Dambock Gomes. 
christiandambock@gmail.com 
https://www.linkedin.com/in/christian-dambock-gomes/
