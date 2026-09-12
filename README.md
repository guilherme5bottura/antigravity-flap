# 🌌 Antigravity Flap

> Jogo arcade casual de precisão e física de antigravidade estilo Flappy Bird, desenvolvido com HTML5 Canvas, Web Audio API, Cloud Firestore para leaderboard global e deploy contínuo no Firebase Hosting.

🎮 **[Jogar Online Agora](https://antigravity-flap-771a.web.app)**

---

## 🕹️ Mecânica e Gameplay

- **🛸 Disco Voador Alienígena Clássico**: Assuma o comando do autêntico disco voador retrô dos filmes clássicos de ficção científica dos anos 50/60! A nave é redondinha, com cúpula de vidro transparente, piloto ET cabeçudo de olhos pretos, luzinhas circulares giratórias coloridas e feixe/raio abdutor de sustentação antigravitacional.
- **⚡ Velocidade Progressiva**: Conforme a pontuação sobe, a velocidade de deslocamento dos propulsores acelera, testando os seus reflexos em níveis arcade cada vez mais intensos!
- **🛸 Fase 2 (Score 20+) - Pilares Oscilantes**: Os pilares energéticos passam a se mover para cima e para baixo em trajetórias aleatórias pelo campo de jogo.
- **⚠️ Fase 3 (Score 30+) - Portais Compactadores**: Alguns obstáculos entram em modo de contenção e se fecham lentamente conforme você se aproxima, exigindo timing de voo milimétrico.
- **Física Gravitacional Suave**: A força da gravidade puxa a nave continuamente para baixo com rotação e inclinação dinâmica.

---

## 🚀 Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3 Moderno (Glassmorphism, CSS Grid/Flexbox) e JavaScript puro (Vanilla ES6+).
- **Renderização**: Canvas API de alta performance com física vetorial e sistema de partículas procedurais.
- **Áudio Autônomo**: Web Audio API nativa com sintetizadores de som dinâmicos (efeitos de flap, pontuação, colisão e fanfarra de recorde) sem dependências externas.
- **Backend & Database**: Firebase Cloud Firestore (SDK Modular v10) para sincronização e persistência dos recordes mundiais em tempo real.
- **Hosting**: Firebase Hosting com CDN global ultrarrápida e certificado SSL automático.

---

## 🏆 Leaderboard Global

O placar é sincronizado diretamente com o **Cloud Firestore**. Os 5 melhores jogadores são exibidos no Hall da Fama tanto na tela inicial quanto na tela de Game Over.
Em caso de falta de conexão com a internet, o jogo utiliza automaticamente o `localStorage` do navegador para manter o progresso salvo.

---

## 🛠️ Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/guilherme5bottura/antigravity-flap.git
   cd antigravity-flap
   ```

2. Abra o arquivo `public/index.html` em qualquer navegador web, ou execute um servidor estático local:
   ```bash
   npx serve public
   ```

---

## ☁️ Deploy no Firebase

Para publicar alterações no Firebase Hosting:

```bash
npx firebase-tools deploy
```

---

Desenvolvido com o **Google Antigravity**.
