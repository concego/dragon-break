# DESIGN.md - Dragon Break

## Conceito
Port fiel dos classicos do Brick Game com controle por acelerometro.
Inovacao: controle sem toque — nao conflita com TalkBack (Android).

## Jogos
- Breakout, Racing, Snake, Tank, Frogger, Space Invaders

## Controles (landscape, botoes fisicos voltados para o jogador)
- Inclina direita/esquerda: move horizontal
- Inclina frente/tras: move vertical  
- Shake leve: acao (atirar, pular)
- Calibracao: posicao atual = centro (ao iniciar)

## Snake — regras especiais
- Ignora comando 180 impossivel (cobra vai reto)
- Dead zone generosa para evitar virada acidental

## Audio
- Web Audio API sintetizando chip original: 2 ondas quadradas + 1 triangular + 1 ruido branco
- Efeitos sonoros via ZzFX

## Tela de Teste
Obrigatoria antes dos jogos. Mostra feedback de cada movimento em tempo real.

## Filosofia
Inclusao digital — cego e vidente jogam o mesmo jogo.
Nao e audiogame. Sem versao acessivel separada. Projeto ECJ.
