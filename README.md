# 🟨 Dash Cube (1.15.7)

Jogo de plataforma de ritmo no estilo **Geometry Dash**, feito em **um único arquivo HTML**. Pule, desvie de espinhos, serras e projéteis, atravesse portais de gravidade e velocidade e complete 20 mapas, cada um com sua própria música. Funciona no computador e no celular, sem instalar nada.

<!-- Adicione aqui prints ou um GIF do jogo -->

---

## ✨ Recursos

- **20 mapas em 5 abas:** Clássicos, Ritmo Neon, Orbs, Infernal e Metal
- **Música própria em cada mapa**, gerada em tempo real pelo navegador (nada de arquivos de áudio)
- **Skins:** 10 prontas e 6 espaços para criar as suas no editor de pixel art
- **Modo treino** com checkpoints
- **Editor de fases:** crie, salve em arquivo e jogue fases suas ou de amigos
- **Multiplayer (beta):** corrida entre dois jogadores usando só um código de sala
- **Configurações:** volume, rastros, qualidade gráfica e duplo clique (macro, beta)
- **Recordes salvos** no próprio navegador

## 🎮 Como jogar

| Ação | Teclado | Celular |
|---|---|---|
| Pular (segure para pular sempre que cair) | `Espaço` ou `↑` | Toque na tela |
| Som ligado/desligado | `M` | Botão "Som" |
| Voltar | `Esc` | Botão "Lobby" |
| Marcar checkpoint (treino) | `C` | Botão "Checkpoint" |
| Apagar checkpoint (treino) | `X` | — |

### Obstáculos e mecânicas

- **Espinhos** no chão e no teto e **serras** giratórias matam. **Blocos** servem de plataforma.
- **Pad amarelo:** lança você bem alto.
- **Orb amarelo:** toque no ar sobre ele para pular de novo.
- **Projéteis rápidos:** baixos pedem pulo, altos pedem para não pular. **Jatos** só machucam quando acesos.
- **Portais de gravidade:** invertem para o teto (roxo ▲) ou para o chão (rosa ▼).
- **Portais de velocidade:** verde (lento), azul (normal), laranja (rápido) e vermelho (muito rápido).
- **Portal de teletransporte (ciano ✦):** joga você no teto, e você cai direto em cima do próximo perigo.

## 🗺️ Mapas

| Aba | Mapas |
|---|---|
| **1 · Clássicos** | Primeiros Passos · Neon Rush · Fogo Cruzado · Caos Total |
| **2 · Ritmo Neon** | Galáxia Pixel · Sonhos Elétricos · Batida Neon · Pulso Final |
| **3 · Orbs** | Órbita · Cristal Quebrado · Eclipse · Colapso |
| **4 · 🔥 Infernal** | Portal do Inferno · Abismo Invertido · Velocidade Infernal · Impossível |
| **5 · 🤘 Metal** | Aço Ardente · Trovão de Aço · Sinfonia Sombria · Apocalipse |

As abas 4 e 5 têm fundo de fogo, portais de gravidade, velocidade e teletransporte, e velocidade máxima. A aba 5 tem guitarras distorcidas, bumbo duplo e riffs de rock/metal.

## 🛠️ Editor de fases

No menu, abra **FASES** > **CRIAR FASE**:

- **Criar fase:** toque para colocar itens, arraste para rolar. Itens: espinho, bloco, espinho de teto, serra, pad, orb, projétil, jato, portais de gravidade e de velocidade, e borracha.
- **Salvar:** gera um arquivo `.dashcube` com o nome da fase. Envie para quem quiser jogar.
- **Entrar em uma fase:** escolha um arquivo `.dashcube`. Sem o arquivo não dá para entrar. Depois você pode **Jogar** ou **Editar**.
- **Testar:** joga a fase direto do editor.
- O editor guarda um rascunho automaticamente no navegador.

> Os portais de teletransporte e os de velocidade lenta/muito rápida ainda não estão disponíveis no editor, só nos mapas infernais.

## 👥 Multiplayer (beta)

Corrida entre dois jogadores: vence quem chegar primeiro ao final.

1. Um jogador abre **MULTIPLAYER (BETA)**, aceita o aviso e toca em **Criar sala**. Aparece um **código de 5 caracteres**.
2. O outro jogador digita o código em **Entrar** e conecta.
3. O anfitrião escolhe o mapa (inclusive uma fase sua carregada do editor) e toca em **Iniciar corrida**.

**Importante:**

- Precisa de internet. A conexão é feita direto entre os jogadores (WebRTC), usando o serviço público [PeerJS](https://peerjs.com/) só para encontrar a sala.
- Em algumas redes (principalmente de celular) a conexão pode falhar.
- Os recordes não são salvos em partidas multiplayer.

## 🎨 Skins

Escolha entre 10 skins prontas (Clássico, Robô, Fantasma, Sapo, Panda, Neon, Lava, Ouro, Oceano e Arco-íris) ou use **Copiar e editar** para criar a sua em uma grade de 8×8 pixels, com 16 cores, preencher, espelhar e limpar. Até 6 skins próprias ficam salvas no navegador.

## ⚙️ Configurações

- Volume da música e dos efeitos, e som geral
- Rastros no chão
- Qualidade gráfica: Baixo, Médio, Alto e Ultra
- **Duplo clique (macro) — beta:** dá um segundo clique automático depois do seu toque, com atraso ajustável. Com ela ligada, os recordes não são salvos.
- Apagar recordes

## 🚀 Como rodar

Baixe o arquivo `Dash Cube 1.15.7.html` e abra com um clique duplo no navegador (computador ou celular). Não precisa instalar nada. Só o multiplayer precisa de internet.

## 🧰 Tecnologias

- HTML5 Canvas 2D
- Web Audio API (música e efeitos sintetizados em tempo real)
- WebRTC via PeerJS (multiplayer, carregado só quando você abre o modo)
- `localStorage` (recordes, skins, configurações e rascunho do editor)
- JavaScript puro, sem frameworks e sem etapa de build

## 📌 Observações

- O multiplayer e o duplo clique estão em **beta** e podem ter erros.
- Os dados ficam salvos no navegador. Limpar os dados do site apaga recordes, skins e rascunho.
- Salve suas fases em arquivo `.dashcube` para não perdê-las.
