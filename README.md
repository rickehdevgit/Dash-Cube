# 🟨 Dash Cube (1.16.9)

Jogo de plataforma de ritmo no estilo **Geometry Dash**, feito inteiramente em **um único arquivo HTML**. Pule, desvie de espinhos, serras e projéteis, atravesse portais de gravidade e velocidade e complete 20 mapas, cada um com sua própria trilha sonora gerada em tempo real. Funciona no computador e no celular, sem precisar instalar nada[span_1](start_span)[span_1](end_span)!

<!-- Adicione aqui prints ou um GIF do jogo -->

---

## ✨ Recursos

- **20 mapas divididos em 5 abas:** Clássicos, Ritmo Neon, Orbs, Infernal e Metal[span_2](start_span)[span_2](end_span).
- **Trilha sonora procedural:** Música própria em cada mapa, gerada via Web Audio API pelo navegador (sem arquivos de áudio externos)[span_3](start_span)[span_3](end_span).
- **Skins personalizáveis:** 10 skins prontas e 6 espaços para criar e editar as suas em pixel art (8x8)[span_4](start_span)[span_4](end_span).
- **Modo treino:** Sistema completo com marcação e remoção de checkpoints (`C` e `X`)[span_5](start_span)[span_5](end_span).
- **Editor de fases:** Crie seus próprios desafios, salve em arquivos `.dashcube` e jogue fases suas ou de amigos[span_6](start_span)[span_6](end_span).
- **Multiplayer (Beta):** Jogue online com amigos via WebRTC/PeerJS[span_7](start_span)[span_7](end_span). Escolha entre 3 modos:
  - 🏁 **Corrida:** Corra pelos mapas tradicionais para ver quem chega primeiro[span_8](start_span)[span_8](end_span).
  - 🧗 **Parkour:** Desafie um percurso gerado proceduralmente com saltos duplos e espinhos[span_9](start_span)[span_9](end_span).
  - 🔫 **PvP:** Arena de tiro mano a mano (quem atingir 5 pontos vence)[span_10](start_span)[span_10](end_span).
- **Configurações avançadas:** Ajustes de volume, rastros, qualidade gráfica e um sistema de macro/duplo clique (beta)[span_11](start_span)[span_11](end_span).
- **Persistência local:** Recordes, skins, configurações e rascunhos salvos automaticamente no navegador[span_12](start_span)[span_12](end_span).

## 🎮 Como Jogar

| Ação | Teclado | Celular |
|---|---|---|
| Pular *(segure para pular sempre que cair)* | `Espaço` ou `↑` | Toque na tela |
| Ligar/Desligar Som | `M` | Botão "Som" |
| Voltar ao Lobby / Menu | `Esc` | Botão "Lobby" |
| Marcar Checkpoint *(Modo Treino)* | `C` | Botão correspondente |
| Apagar Checkpoint *(Modo Treino)* | `X` | — |
| Atirar *(Modo PvP Arena)* | `F`, `J` ou Clique | Botão "🔫" |

### Mecânicas e Obstáculos
- **Espinhos** (chão/teto) e **Serras giratórias** causam morte instantânea[span_13](start_span)[span_13](end_span). **Blocos** servem como plataformas seguras[span_14](start_span)[span_14](end_span).
- **Pad Amarelo:** Lança o jogador para o alto com força extra[span_15](start_span)[span_15](end_span).
- **Orb Amarelo:** Permite dar um salto duplo no ar ao tocar sobre ele[span_16](start_span)[span_16](end_span).
- **Projéteis e Jatos:** Desvie de projéteis rápidos (baixo = pule, alto = não pule) e jatos acesos[span_17](start_span)[span_17](end_span).
- **Portais de Gravidade:** Invertem a gravidade para o teto (roxo) ou voltam ao chão (rosa)[span_18](start_span)[span_18](end_span).
- **Portais de Velocidade:** Altera o ritmo da corrida (lento, normal, rápido e muito rápido)[span_19](start_span)[span_19](end_span).
- **Portal de Teletransporte (ciano):** Joga o jogador direto para o teto em direção aos perigos[span_20](start_span)[span_20](end_span).

## 🗺️ Mapas

| Categoria | Mapas |
|---|---|
| **1 · Clássicos** | Primeiros Passos · Neon Rush · Fogo Cruzado · Caos Total[span_21](start_span)[span_21](end_span) |
| **2 · Ritmo Neon** | Galáxia Pixel · Sonhos Elétricos · Batida Neon · Pulso Final[span_22](start_span)[span_22](end_span) |
| **3 · Orbs** | Órbita · Cristal Quebrado · Eclipse · Colapso[span_23](start_span)[span_23](end_span) |
| **4 · 🔥 Infernal** | Portal do Inferno · Abismo Invertido · Velocidade Infernal · Impossível[span_24](start_span)[span_24](end_span) |
| **5 · 🤘 Metal** | Aço Ardente · Trovão de Aço · Sinfonia Sombria · Apocalipse[span_25](start_span)[span_25](end_span) |

*As abas 4 e 5 contam com fundos dinâmicos em chamas, alta velocidade, portais avançados e trilhas sonoras pesadas em estilo rock/metal com bumbo duplo e guitarras distorcidas[span_26](start_span)[span_26](end_span).*

## 🛠️ Editor de Fases

No menu principal, abra **FASES** para acessar o criador[span_27](start_span)[span_27](end_span):
- **Criar Fase:** Toque para posicionar elementos e arraste para navegar pela linha do tempo[span_28](start_span)[span_28](end_span).
- **Salvar / Carregar:** Exporte suas criações em arquivos `.dashcube` e compartilhe com outras pessoas[span_29](start_span)[span_29](end_span).
- **Testar:** Experimente a fase diretamente do editor antes de salvá-la[span_30](start_span)[span_30](end_span).

## 👥 Multiplayer (Beta)

Dispute partidas online conectando-se diretamente com um amigo[span_31](start_span)[span_31](end_span):
1. Um jogador abre **MULTIPLAYER**, aceita o aviso e clica em **Criar sala** para gerar um código de 5 caracteres[span_32](start_span)[span_32](end_span).
2. O segundo jogador digita o código na aba **Entrar** para conectar[span_33](start_span)[span_33](end_span).
3. O anfitrião escolhe o modo de jogo (**Corrida**, **Parkour** ou **PvP**) e o mapa/configuração, depois clica em **Iniciar**[span_34](start_span)[span_34](end_span).
*(Nota: A conexão ocorre de forma direta via P2P/PeerJS[span_35](start_span)[span_35](end_span). Redes móveis restritas podem ocasionalmente bloquear a conexão).*

## 🚀 Como Executar

Basta baixar o arquivo `Dash Cube 1.16.9.html` e dar um duplo clique para abri-lo em qualquer navegador moderno (Chrome, Safari, Firefox, Edge)[span_36](start_span)[span_36](end_span). Nenhuma instalação ou servidor local é necessário[span_37](start_span)[span_37](end_span).

## 🧰 Tecnologias Utilizadas

- **HTML5 Canvas 2D** para renderização gráfica e animações[span_38](start_span)[span_38](end_span).
- **Web Audio API** para síntese de som e música em tempo real[span_39](start_span)[span_39](end_span).
- **WebRTC (PeerJS)** para o modo multiplayer peer-to-peer[span_40](start_span)[span_40](end_span).
- **LocalStorage** para salvamento de dados locais[span_41](start_span)[span_41](end_span).
- **JavaScript Moderno (ES6+)** puro, sem dependências externas ou frameworks[span_42](start_span)[span_42](end_span).
