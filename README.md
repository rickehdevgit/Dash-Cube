
# 🟨 Dash Cube (v1.9.8)

Um jogo de plataforma de ritmo no estilo *Geometry Dash*, desenvolvido inteiramente em um **único arquivo HTML**. Pule espinhos, desvie de serras giratórias, projéteis e use orbs para avançar em 12 mapas oficiais com músicas procedurais únicas geradas em tempo real.

> 🚀 **Sem instalação, sem dependências e sem arquivos externos de áudio.** Abra no navegador e jogue no PC ou no celular!

---

## 🆕 Novidades da Versão 1.9.8

- **Multiplayer Simplificado por Código (PeerJS):** Sistema de salas aprimorado! Crie uma sala, receba um código de 5 caracteres e compartilhe com seu amigo para se conectarem rapidamente sem trocar grandes blocos de texto.
- **Exportação e Importação de Fases (`.dashcube`):** No Editor de Fases, agora é possível renomear, salvar e baixar suas criações como arquivos `.dashcube` para compartilhar com amigos ou carregar fases personalizadas.
- **Suporte a Fases Customizadas no Multiplayer:** O anfitrião da sala pode carregar uma fase personalizada criada no editor para jogar em tempo real contra o amigo.
- **Interface e Fluxo Melhorados:** Adição do menu "FASES" para criar, carregar ou continuar rascunhos de fases personalizadas com facilidade.

---

## ✨ Recursos Principais

- **12 Mapas Divididos por Categorias:** Fases desafiadoras com dificuldades progressivas organizadas em abas temáticas, além do slot para fases customizadas.
- **Música Procedural em Tempo Real:** Trilha sonora gerada via **Web Audio API** (melodia, baixo, arpejos, bateria e efeitos) para cada mapa.
- **Editor de Fases e Skins Integrado:** Crie e salve seus próprios mapas e personalize a skin do seu cubo pixel por pixel em uma grade 8x8.
- **Modo Treino:** Pratique trechos difíceis salvando e carregando checkpoints (`C` para salvar, `X` para limpar).
- **Menu de Configurações Completo:** Ajuste volumes, rastros no chão, qualidade gráfica, opção de macro (duplo clique) e reset de recordes.
- **Persistência Local:** Progresso, recordes, rascunhos de fases e skins criadas são salvos no `localStorage`.

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

> 🛠️ **Fase Customizada (Meu Mapa):** Espaço dedicado para criar, exportar em arquivo ou importar fases de amigos no Editor.

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

1. Baixe o arquivo `Dash Cube 1.9.8.html` (ou renomeie para `index.html`).
2. Abra-o em qualquer navegador moderno (Chrome, Firefox, Edge ou Safari), no PC ou celular.
3. Clique ou toque na tela inicial para liberar o áudio e começar a jogar!

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Canvas:** Renderização gráfica 2D a 60 FPS.
- **JavaScript (ES6+):** Física, colisões e lógica geral.
- **Web Audio API:** Síntese procedural de áudio e música em tempo real.
- **PeerJS / WebRTC:** Conexão multiplayer Peer-to-Peer por código de sala.
- **LocalStorage API:** Persistência de dados e salvamento.

