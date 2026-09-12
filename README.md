# 🌌 Antigravity Flap

> Jogo arcade casual de precisão e física de antigravidade estilo Flappy Bird, desenvolvido com HTML5 Canvas, Web Audio API, Cloud Firestore para leaderboard global e deploy contínuo no Firebase Hosting.

🎮 **[Jogar Online Agora](https://antigravity-flap-771a.web.app)**

---

## 🕹️ Mecânica e Gameplay

- **Controle Gravitacional**: Clique com o mouse, toque na tela (mobile) ou pressione `ESPAÇO` / `▲` / `W` para ativar os propulsores iônicos da sonda quântica.
- **Gravidade Dinâmica**: A força da gravidade puxa a cápsula continuamente para baixo, exigindo controle do timing de impulsão.
- **Colunas de Plasma**: Supere os obstáculos energéticos procedurais sem encostar nas barreiras de contenção.
- **Progressão Fluida**: A velocidade e os vãos se ajustam sutilmente com o aumento do score para garantir desafio contínuo.

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
