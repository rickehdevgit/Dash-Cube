# 🟨 Dash Cube

Um jogo de plataforma de ritmo no estilo Geometry Dash, feito em um único arquivo HTML. Pule espinhos, serras e projéteis, atravesse portais de gravidade e velocidade e complete os 12 mapas disponíveis, cada um com a sua própria música e desafios.

> Sem instalação, sem dependências e sem arquivos de áudio. Abra no navegador e jogue, no PC ou no celular.

## ✨ Recursos

- 12 mapas divididos em categorias de dificuldade e ritmo (incluindo Clássicos, Ritmo Neon, Orbs e o modo Editor)
- Música original para cada mapa, gerada em tempo real com a Web Audio API (melodia, baixo, arpejos, bateria e eco)
- Menu animado com formas neon que pulsam, tela de ajuda e painel de estatísticas
- Menu de configurações completo: volume da música, volume dos efeitos, som geral, rastros no chão, opções de qualidade gráfica, duplo clique (macro) e opção para apagar recordes
- Obstáculos e mecânicas variados: espinhos, blocos, teto, serras giratórias, jump pads, orbs, portais de gravidade, portais de velocidade, projéteis rápidos e jatos
- Sistema de personalização de Skins e Editor completo de fases e de skins integrado
- Modo de Treino com marcação de checkpoints (teclas C e X)
- Modo Multiplayer (BETA) via WebRTC para correr contra um amigo trocando códigos de conexão
- Progresso, recordes e configurações salvos automaticamente no aparelho (`localStorage`)
- Compatibilidade total com teclado, mouse e comandos por toque

## 🗺️ Mapas e Fases

O jogo conta com uma seleção diversificada de fases progressivas que testam a agilidade, reflexos e sincronia com o ritmo da música.

| # | Mapa | Dificuldade / Tag principal |
|---|------|-----------------------------|
| 1 | Primeiros Passos | Jump pads |
| 2 | Neon Rush | Portais de velocidade |
| 3 | Fogo Cruzado | Serras e gravidade |
| 4 | Caos Total | Tudo junto |
| 5 | Galáxia Pixel | Projéteis e jatos |
| 6 | Sonhos Elétricos | Rajadas de projéteis |
| 7 | Batida Neon | Gravidade e rajadas |
| 8 | Pulso Final | Tudo e projéteis |
| 9 | Órbita | Orbs e serras altas |
| 10 | Cristal Quebrado | Orbs e gravidade |
| 11 | Eclipse | Mistura total |
| 12 | Colapso / Meu Mapa | Desafio final e Editor |

## 🧩 Obstáculos e Elementos

| Elemento | O que faz |
|----------|-----------|
| **Espinhos e Serras** | Causam morte instantânea ao encostar. |
| **Blocos** | Permitem pousar em cima, mas bater nas laterais resulta em morte. |
| **Pad Amarelo** | Lança o cubo em um salto de alta altitude. |
| **Portais de Velocidade** | Aceleram ou retornam a velocidade padrão do cubo. |
| **Portal Roxo** | Inverte a gravidade, fazendo o cubo correr pelo teto. |
| **Orb Amarelo** | Permite executar um salto no ar ao tocar sobre ele. |
| **Projéteis e Jatos** | Obstáculos dinâmicos que exigem atenção ao timing e à altura. |

## 🎮 Controles

| Ação | Teclado | Mouse / Toque |
|------|---------|---------------|
| Pular / Subir | `Espaço` ou `↑` (segure para pular de novo ao cair) | Clique / Toque na tela |
| Marcar Checkpoint (Treino) | `C` | Botão na tela de jogo |
| Apagar Checkpoint | `X` | — |
| Silenciar / Ativar Som | `M` | Botão de Som / Menu de Configurações |
| Voltar / Pausar | `Esc` | Botão "Lobby" ou "Menu" |

## 🚀 Como Rodar

1. Baixe ou salve o arquivo do jogo (por exemplo, `Dash Cube.html`) no seu computador ou dispositivo.
2. Dê um duplo clique no arquivo para abri-lo em qualquer navegador moderno (Google Chrome, Firefox, Microsoft Edge ou Safari).
3. Toque na tela inicial para iniciar o áudio e divirta-se jogando!

> **Nota sobre o áudio:** Por restrições dos navegadores modernos, o sistema de som e música procedural só é ativado após a primeira interação (toque ou tecla) com a página.

## 🛠️ Tecnologias Utilizadas

- **HTML5 Canvas** para renderização gráfica e animações fluidas a 60 FPS.
- **JavaScript (ES6+)** puro para toda a lógica de física, colisões e gerenciamento de estados.
- **Web Audio API** para síntese procedural de músicas e efeitos sonoros em tempo real.
- **WebRTC API** para o recurso de partidas multiplayer P2P.
- **LocalStorage** para persistência de recordes, configurações e skins customizadas.
