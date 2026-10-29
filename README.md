# 🟨 Dash Cube

Um jogo de plataforma de ritmo no estilo *Geometry Dash*, desenvolvido inteiramente em um **único arquivo HTML**. Pule espinhos, desvie de serras giratórias, projéteis e use orbs para avançar em 12 mapas oficiais com músicas procedurais únicas geradas em tempo real.

> 🚀 **Sem instalação, sem dependências e sem arquivos externos de áudio.** Abra no navegador e jogue, no PC ou no celular!

---

## ✨ Recursos

- **12 Mapas Divididos por Categorias:** Fases desafiadoras com dificuldades progressivas organizadas em abas temáticas, além do modo Editor.
- **Música Procedural em Tempo Real:** Cada fase possui sua própria trilha sonora gerada dinamicamente via **Web Audio API** (melodia, baixo, arpejos, bateria e efeitos).
- **Editor de Fases e Skins Integrado:** Crie e salve seus próprios mapas e personalize o visual do seu cubo em um editor pixel art 8x8.
- **Modo Treino:** Pratique trechos difíceis salvando e carregando checkpoints (`C` para salvar, `X` para limpar).
- **Multiplayer (BETA):** Conecte-se com um amigo via WebRTC por códigos de sala e corram no mesmo mapa em tempo real.
- **Menu de Configurações Completo:** Ajuste volumes, rastros no chão, qualidade gráfica, opção de macro (duplo clique) e reset de recordes.
- **Persistência Total:** Progresso, recordes, skins e mapas criados são salvos automaticamente no `localStorage`.

---

## 🗺️ Mapas e Fases (Divididos por Categoria)

### 🟡 Aba 1: Clássicos
| # | Mapa | Dificuldade | Elemento Principal |
|---|------|-------------|--------------------|
| 1 | Primeiros Passos | Fácil | Jump pads |
| 2 | Neon Rush | Médio | Portais de velocidade |
| 3 | Fogo Cruzado | Difícil | Serras e gravidade |
| 4 | Caos Total | Insano | Tudo junto |

### 🟣 Aba 2: Ritmo Neon
| # | Mapa | Dificuldade | Elemento Principal |
|---|------|-------------|--------------------|
| 5 | Galáxia Pixel | Médio | Projéteis e jatos |
| 6 | Sonhos Elétricos | Difícil | Rajadas de projéteis |
| 7 | Batida Neon | Insano | Gravidade e rajadas |
| 8 | Pulso Final | Lendário | Tudo e projéteis |

### 🔵 Aba 3: Orbs & Desafios Avançados
| # | Mapa | Dificuldade | Elemento Principal |
|---|------|-------------|--------------------|
| 9 | Órbita | Difícil | Orbs e serras altas |
| 10 | Cristal Quebrado | Insano | Orbs e gravidade |
| 11 | Eclipse | Insano | Mistura total |
| 12 | Colapso | Lendário | Desafio final |

> 🛠️ **Meu Mapa:** Slot especial dedicado para criar, editar e jogar sua própria fase no Editor.

---

## 🧩 Obstáculos e Elementos

| Elemento | O que faz |
|----------|-----------|
| **Espinhos e Serras** | Causam morte instantânea ao menor contato. |
| **Blocos** | Superfícies sólidas para pousar (bater lateralmente resulta em morte). |
| **Pad Amarelo** | Lança o cubo em um salto alto automático. |
| **Orb Amarelo** | Permite dar um salto no ar ao tocar sobre ele. |
| **Portais de Velocidade** | Aceleram (laranja) ou retornam a velocidade padrão (azul). |
| **Portal de Gravidade** | Inverte a gravidade, fazendo o cubo correr pelo teto (roxo). |
| **Projéteis e Jatos** | Obstáculos rítmicos e móveis que exigem atenção ao tempo e à altura. |

---

## 🎮 Controles

| Ação | Teclado | Mouse / Toque |
|------|---------|---------------|
| **Pular** | `Espaço` ou `Seta ↑` *(segure para pular ao cair)* | Clique / Toque na tela |
| **Marcar Checkpoint (Treino)** | Tecla `C` | Botão na tela |
| **Apagar Checkpoint (Treino)** | Tecla `X` | — |
| **Ligar/Desligar Som** | Tecla `M` | Menu de Configurações |
| **Selecionar Fase** | Teclas `1` a `4` (referente à aba aberta) | Clique no cartão do mapa |
| **Trocar Abas** | Teclas `Seta ←` / `Seta →` | Clique nos botões de abas |
| **Pausar / Voltar** | Tecla `Esc` | Botão "Lobby" ou "Menu" |

---

## 🚀 Como Rodar

1. Baixe o arquivo `Dash Cube (3).html` (ou renomeie para `index.html`).
2. Abra-o em qualquer navegador moderno (Chrome, Firefox, Edge ou Safari), no PC ou celular.
3. Clique ou toque na tela inicial para liberar o som e começar a jogar!

> **Nota:** Navegadores exigem um clique ou toque inicial na tela para liberar o áudio procedural.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Canvas:** Renderização gráfica 2D a 60 FPS.
- **JavaScript (ES6+):** Física, colisões e lógica geral.
- **Web Audio API:** Síntese procedural de áudio e música em tempo real.
- **WebRTC API:** Conexão multiplayer Peer-to-Peer (P2P).
- **LocalStorage API:** Salvamento de recordes, configurações, skins e fases criadas.

