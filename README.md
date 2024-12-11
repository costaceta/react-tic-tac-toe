# Tic-Tac-Toe com React e ViteJS

## Descrição
Este projeto é uma implementação do clássico jogo da velha (Tic-Tac-Toe) desenvolvido com **React** e utilizando o **ViteJS** como ferramenta de build. O objetivo do projeto é criar um jogo interativo, simples e funcional para praticar conceitos de React, como estados, componentes e manipulação de eventos.

## Link da Aplicação

[React Tic-Tac-Toe](https://costaceta.github.io/react-tic-tac-toe/)


## Funcionalidades
- Jogabilidade para dois jogadores.
- Destaque do jogador atual.
- Verificação automática de vitória ou empate.
- Reinício do jogo sem recarregar a página.

## Tecnologias Utilizadas
- [React](https://reactjs.org/): Biblioteca para construção de interfaces de usuário.
- [ViteJS](https://vitejs.dev/): Ferramenta moderna de build para desenvolvimento rápido.
- [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS): Estilização da interface.

## Pré-requisitos
Antes de iniciar, certifique-se de ter as seguintes ferramentas instaladas em sua máquina:
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

## Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/costaceta/react-tic-tac-toe.git
   ```

2. **Acesse o diretório do projeto:**
   ```bash
   cd react-tic-tac-toe
   ```

3. **Instale as dependências:**
   ```bash
   npm install
   # ou
   yarn install
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   # ou
   yarn dev
   ```

5. **Abra o jogo no navegador:**
   O Vite exibirá um link, geralmente `http://localhost:5173`. Acesse-o para jogar o Tic-Tac-Toe.

## Estrutura do Projeto
```
├── public
│   ├── bg-pattern-dark.png
│   ├── bg-pattern.png
│   └── game-logo.png
├── src
│   ├── components
│   │   ├── GameBoad.jsx
│   │   ├── GameOver.jsx
│   │   ├── Log.jsx
│   │   └── Player.jsx
│   ├── App.jsx
│   ├── index.jsx
│   └── index.css
├── package.json
├── vite.config.js
└── README.md
```

- **components/**: Contém os componentes reutilizáveis do projeto.
- **App.jsx**: Componente principal que gerencia o estado do jogo.
- **index.css**: Arquivo de estilização.


## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

---

Desenvolvido com ❤️ por [Rafael Costa](https://github.com/costaceta).
