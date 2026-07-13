# 🎮 Dragon Brick

Port fiel dos clássicos do **Brick Game** (aquele console de tijolinho dos anos 90), com controle por **acelerômetro** e foco em **inclusão digital**.

> Cego e vidente jogando o mesmo jogo, na mesma tela. Sem versão paralela, sem modo especial separado.

## 🕹️ Jogos

| Jogo | Status |
|---|---|
| Breakout | 🚧 Em desenvolvimento |
| Racing | 🚧 Em desenvolvimento |
| Snake | 🚧 Em desenvolvimento |
| Tank | 🚧 Em desenvolvimento |
| Frogger | 🚧 Em desenvolvimento |
| Space Invaders | 🚧 Em desenvolvimento |

## 📱 Controles (Acelerômetro)

Segure o celular em **landscape** com os botões físicos voltados para você:

| Movimento | Ação |
|---|---|
| Inclina direita | → Direita |
| Inclina esquerda | ← Esquerda |
| Inclina pra frente | ↑ Cima |
| Inclina pra trás | ↓ Baixo |
| Shake leve | 🔫 Ação (atirar, pular) |

### Por que acelerômetro?
Leitores de tela como o TalkBack (Android) interceptam todos os gestos na tela. O acelerômetro é um sensor físico — não há conflito. Resultado: o mesmo controle funciona para todos os jogadores.

## 🔊 Áudio

Som autêntico do hardware original:
- **4 canais:** 2 ondas quadradas + 1 triangular + 1 ruído branco (igual ao chip do Brick Game original)
- Sintetizado via **Web Audio API** — sem arquivos externos
- Efeitos sonoros via **ZzFX**

## 🎯 Filosofia

Este projeto é parte do **Eu Concego Jogar (ECJ)** — missão de inclusão digital para pessoas com deficiência visual.

- Não é um audiogame
- Não tem "modo acessível" separado
- Todo mundo joga a mesma coisa

## 🗂️ Estrutura

```
dragon-brick/
├── index.html
├── test/
├── games/
│   ├── breakout/
│   ├── racing/
│   ├── snake/
│   ├── tank/
│   ├── frogger/
│   └── space-invaders/
├── engine/
│   ├── accelerometer.js
│   ├── audio.js
│   └── renderer.js
└── assets/
    └── fonts/
```

## 🔗 Links

- Projeto: [Eu Concego Jogar](https://euconcego.com.br)
- Portfólio: [site.zapia.com/0alwlra4](https://site.zapia.com/0alwlra4)
