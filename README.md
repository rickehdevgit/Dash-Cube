# 🎮 Dash Cube v1.25.0

**Dash Cube** é um jogo 2D de ritmo e plataforma em HTML5 com estética retrô *pixel art*. Ele foi desenvolvido para rodar diretamente no navegador (PC e mobile) sem a necessidade de instalações, dependências ou servidores externos dedicados.

---

## ✨ Destaques do Jogo

- **🏁 30+ Fases Principais:** Divididas por categorias e estilos visuais únicos com progressão contínua de dificuldade.
- **🌐 Multiplayer P2P em Tempo Real:** Conexão direta entre jogadores via código de sala (5 dígitos), sem cadastro ou servidores intermediários.
- **✎ Editor de Fases Nativo:** Ferramenta integrada para criar, testar e exportar/importar fases personalizadas no formato `.dashcube`.
- **🎨 Customização Completa:** Editor de *pixel art* para criar skins personalizadas, além de sistema de loja com rastros de partículas, efeitos de morte e conquistas.
- **🎵 Trilha Sonora Procedural:** Áudio dinâmico sintetizado via *Web Audio API*, com BPM sincronizado em tempo real à física e aos obstáculos da fase.
- **🎮 Suporte Multiplataforma:** Compatibilidade total com teclado e controles *touchscreen* responsivos para dispositivos móveis.

---

## 📂 Categorias e Temas de Fases

A campanha principal conta com mais de 30 fases organizadas nos seguintes blocos temáticos:

1. **Neon Rush (Fases Introdutórias):**
   - Estética vibrante em tons de azul ciano e rosa choque.
   - Foco em apresentar as mecânicas de salto, tempo de reação, ritmo e obstáculos móveis iniciais.

2. **Metal Thrash (Fases Intermediárias):**
   - Estilo industrial e agressivo com paletas escuras, cinzas metálicas e detalhes em vermelho.
   - Velocidade elevada, saltos de precisão e introdução de plataformas falsas.

3. **Synthwave (Fases Avançadas):**
   - Inspirado na estética anos 80, com grades de perspectiva, pores do sol geométricos e sintetizadores marcantes.
   - Exige reflexos rápidos com transições frequentes de velocidade e gravidade.

4. **Galáxia Pixel (Fases Difíceis):**
   - Cenário espacial em *pixel art* com nebulosas e estrelas ao fundo.
   - Desafios complexos com múltiplos portais de alteração de estado do personagem.

5. **Fases Espaciais / Hardcore (Desafio Final):**
   - O nível mais alto de dificuldade do jogo.
   - Ambientes com gravidade alterada, efeitos visuais intensos e trilhas sonoras de ritmo acelerado.

---

## 🌐 Modos de Jogo

- **Modo Campanha:** Progressão linear pelas fases principais do jogo.
- **Multiplayer P2P:**
  - **Corridas 1v1:** Disputa direta para ver quem chega primeiro ao final do percurso.
  - **Parkour:** Percursos competitivos ou cooperativos focados na precisão dos saltos.
  - **PvP:** Confronto direto em arenas adaptadas.
  - **Defesa da Torre Co-op:** Modo cooperativo focado em defender pontos do mapa contra ondas de obstáculos.
- **Editor de Fases:** Criação livre de mapas com ajuste de BPM, distribuição de portais, espinhos e blocos.

---

## 🕹️ Como Jogar

1. Abra o arquivo `DashCube1_25_0.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
2. Escolha o modo de jogo no menu principal.
3. **Controles:**
   - **PC:** Tecla `Espaço`, `Seta para Cima` ou teclas `A` / `D`.
   - **Mobile:** Toque em qualquer parte da tela.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Canvas 2D:** Renderização dos gráficos e sistema de partículas.
- **Web Audio API:** Síntese de áudio procedural e sincronização de ritmo.
- **WebRTC / PeerJS:** Comunicação multiplayer peer-to-peer em tempo real.
- **JavaScript (ES6+):** Motor de física, lógica de jogo e serialização em arquivo único.
