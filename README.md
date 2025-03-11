# ⚔️ Matador de Monstros

<div align="center">
<img src="https://github.com/portfolio-projetos-dev/matador-monstros/raw/main/.gitassets/capa.png" width="350" />

<div data-badges>
    <img src="https://img.shields.io/github/stars/portfolio-projetos-dev/matador-monstros?style=for-the-badge" alt="GitHub stars" />
    <img src="https://img.shields.io/github/forks/portfolio-projetos-dev/matador-monstros?style=for-the-badge" alt="GitHub forks" />
    <img src="https://img.shields.io/github/issues/portfolio-projetos-dev/matador-monstros?style=for-the-badge" alt="GitHub issues" />
</div>

<div data-badges>
<img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D" alt="Vue.js" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</div>
</div>

O projeto Matador de Monstro é um jogo que coloca o jogador em uma batalha direta contra um monstro. Ambos possuem barras de vida, e o objetivo é derrotar o adversário antes de ser derrotado. A interação ocorre por meio de quatro botões principais: **Atacar**, que realiza um ataque normal e causa dano moderado; **Ataque Especial**, que inflige mais dano; **Curar**, que permite ao jogador recuperar parte de sua vida; e **Desistir**, caso o jogador decida encerrar o jogo.

A cada turno, o jogador escolhe uma ação, e o monstro automaticamente contra-ataca, reduzindo a vida do jogador. O jogo continua até que a vida de um dos dois chegue a zero. O resultado pode ser uma **vitória**, caso o jogador derrote o monstro antes de ser derrotado; uma **derrota**, se o jogador perder toda sua vida primeiro; ou um **empate**, se ambos chegarem a zero no mesmo turno.

## 🖥️ Como rodar este projeto 🖥️

### Requisitos:

- [Node.js](https://nodejs.org/pt) instalado

### Execução:

1. Clone este repositório:

   ```sh
   git clone https://github.com/portfolio-projetos-dev/matador-monstros
   ```

2. Acesse o diretório do projeto:

   ```sh
   cd matador-monstros
   ```

3. Instale as dependências:

   ```sh
   npm install
   ```

4. Inicie o servidor:

   ```sh
   npm run dev
   ```

5. Acesse o projeto em [http://localhost:5173](http://localhost:5173).

## 🗒️ Features do projeto 🗒️

- Barra de vida para o jogador e para o monstro, exibindo os status de ambos.
- Botão **Atacar** para realizar ataques normais que causam dano moderado ao monstro.
- Botão **Ataque Especial** para realizar ataques mais poderosos com maior dano.
- Botão **Curar** para permitir que o jogador recupere parte de sua vida.
- Botão **Desistir** para encerrar o jogo imediatamente.
- Sistema de turnos, onde o monstro realiza um contra-ataque automático após cada ação do jogador.
- Exibição do resultado final (vitória, derrota ou empate) ao término da partida.
- Interface simples e intuitiva para facilitar a interação do jogador.
- Feedback visual para indicar as ações realizadas (ataque, cura ou dano recebido).
- Possibilidade de reiniciar o jogo após o término de uma partida.

![](https://github.com/portfolio-projetos-dev/matador-monstros/raw/main/.gitassets/2.jpg)

![](https://github.com/portfolio-projetos-dev/matador-monstros/raw/main/.gitassets/3.jpg)

## 💎 Links úteis 💎

- [Vue](https://vuejs.org/guide/introduction)
