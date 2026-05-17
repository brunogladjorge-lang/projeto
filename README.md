# 🟡 PAC-MAN Remaster

Remasterização do clássico Pac-Man (Namco, 1980) desenvolvida com Node.js, Express e Canvas HTML5.

Pré-requisitos
- Node.js v18+ instalado

npm install

npm start


Acesse no navegador: **http://localhost:3000**

## 📄 Páginas

| Rota | Descrição |
|------|-----------|
| `/` | Página principal com detalhes do jogo |
| `/devs` | Informações dos desenvolvedores |
| `/game` | Jogo embarcado + instruções |

## 🎮 Controles

- **Setas / WASD** — Mover o Pac-Man
- **ENTER / SPACE** — Iniciar jogo / Próxima fase
- **Mobile** — Deslize para mover

## 🏗️ Estrutura do Projeto


pacman-remaster/
├── server.js              ← Servidor Express (Node.js)
├── package.json
├── views/
│   ├── index.ejs          ← Página principal
│   ├── devs.ejs           ← Página dos desenvolvedores
│   ├── game.ejs           ← Página do jogo
│   └── partials/
│       ├── header.ejs
│       └── footer.ejs
└── public/
    ├── css/style.css      ← Estilo completo (tema neon)
    └── js/game.js         ← Motor do jogo (Canvas + BFS AI)


## 🔧 Tecnologias

- **Node.js** + **Express** — Servidor web
- **EJS** — Template engine
- **Canvas 2D API** — Renderização do jogo
- **Web Audio API** — Sons procedurais (sem arquivos externos)
- **BFS (Busca em Largura)** — IA de pathfinding dos fantasmas

## 📚 Referências

- Pac-Man original (Namco, 1980)
- [The Pac-Man Dossier](https://www.gamedeveloper.com/design/the-pac-man-dossier) — Jamey Pittman (2009)
- [MDN Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- [MDN Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
