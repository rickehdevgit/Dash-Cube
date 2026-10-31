🟨 Dash Cube (1.18.0)
Jogo de plataforma de ritmo no estilo Geometry Dash, feito inteiramente em um único arquivo HTML. Pule, desvie de espinhos, serras e projéteis, atravesse portais de gravidade e velocidade e complete 21 mapas, cada um com sua própria trilha sonora gerada em tempo real. Funciona no computador e no celular, sem precisar instalar nada!
<!-- Adicione aqui prints ou um GIF do jogo -->
✨ Recursos
 * 21 mapas divididos em 5 abas: Clássicos, Ritmo Neon, Orbs, Infernal e Metal.
 * Trilha sonora procedural: Música própria em cada mapa, gerada via Web Audio API pelo navegador (sem arquivos de áudio externos).
 * Skins personalizáveis: 10 skins prontas e 6 espaços para criar e editar as suas em pixel art (8x8).
 * Modo treino: Sistema completo com marcação e remoção de checkpoints (C e X).
 * Editor de fases: Crie seus próprios desafios, salve em arquivos .dashcube e jogue fases suas ou de amigos.
 * Multiplayer (Beta): Jogue online com amigos via WebRTC/PeerJS. Escolha entre 4 modos:
   * 🏁 Corrida: Corra pelos mapas tradicionais para ver quem chega primeiro.
   * 🧗 Parkour: Desafie um percurso gerado proceduralmente com saltos duplos e espinhos.
   * 🔫 PvP: Arena de tiro mano a mano (quem atingir 5 pontos vence).
   * 🏰 Defesa da Torre: Modo co-op de defesa.
 * Configurações avançadas: Ajustes de volume, rastros, qualidade gráfica e um sistema de macro/duplo clique (beta).
 * Persistência local: Recordes, skins, configurações e rascunhos salvos automaticamente no navegador.
🎮 Como Jogar
| Ação | Teclado | Celular |
|---|---|---|
| Pular (segure para pular sempre que cair) | Espaço ou ↑ | Toque na tela |
| Ligar/Desligar Som | M | Botão "Som" |
| Voltar ao Lobby / Menu | Esc | Botão "Lobby" |
| Marcar Checkpoint (Modo Treino) | C | Botão correspondente |
| Apagar Checkpoint (Modo Treino) | X | — |
| Atirar (Modo PvP Arena) | F, J ou Clique | Botão "🔫" |
Mecânicas e Obstáculos
 * Espinhos (chão/teto) e Serras giratórias causam morte instantânea. Blocos servem como plataformas seguras.
 * Pad Amarelo: Lança o jogador para o alto com força extra.
 * Orb Amarelo: Permite dar um salto duplo no ar ao tocar sobre ele.
 * Projéteis e Jatos: Desvie de projéteis rápidos (baixo = pule, alto = não pule) e jatos acesos.
 * Portais de Gravidade: Invertem a gravidade para o teto (roxo) ou voltam ao chão (rosa).
 * Portais de Velocidade: Altera o ritmo da corrida (lento, normal, rápido e muito rápido).
 * Portal de Teletransporte (ciano): Joga o jogador direto para o teto em direção aos perigos.
🗺️ Mapas
| Categoria | Mapas |
|---|---|
| 1 · Clássicos | Primeiros Passos · Neon Rush · Fogo Cruzado · Caos Total |
| 2 · Ritmo Neon | Galáxia Pixel · Sonhos Elétricos · Batida Neon · Pulso Final |
| 3 · Orbs | Órbita · Cristal Quebrado · Eclipse · Colapso |
| 4 · 🔥 Infernal | Portal do Inferno · Abismo Invertido · Velocidade Infernal · Impossível |
| 5 · 🤘 Metal | Aço Ardente · Trovão de Aço · Sinfonia Sombria · Apocalipse |
As abas 4 e 5 contam com fundos dinâmicos em chamas, alta velocidade, portais avançados e trilhas sonoras pesadas em estilo rock/metal com bumbo duplo e guitarras distorcidas.
🛠️ Editor de Fases
No menu principal, abra FASES para acessar o criador:
 * Criar Fase: Toque para posicionar elementos e arraste para navegar pela linha do tempo.
 * Salvar / Carregar: Exporte suas criações em arquivos .dashcube e compartilhe com outras pessoas.
 * Testar: Experimente a fase diretamente do editor antes de salvá-la.
👥 Multiplayer (Beta)
Dispute partidas online conectando-se diretamente com um amigo:
 * Um jogador abre MULTIPLAYER, aceita o aviso e clica em Criar sala para gerar um código de 5 caracteres.
 * O segundo jogador digita o código na aba Entrar para conectar.
 * O anfitrião escolhe o modo de jogo (Corrida, Parkour, PvP ou Defesa da Torre) e o mapa/configuração, depois clica em Iniciar.
   (Nota: A conexão ocorre de forma direta via P2P/PeerJS. Redes móveis restritas podem ocasionalmente bloquear a conexão).
🚀 Como Executar
Basta baixar o arquivo Dash Cube 1.18.0.html e dar um duplo clique para abri-lo em qualquer navegador moderno (Chrome, Safari, Firefox, Edge). Nenhuma instalação ou servidor local é necessário.
🧰 Tecnologias Utilizadas
 * HTML5 Canvas 2D para renderização gráfica e animações.
 * Web Audio API para síntese de som e música em tempo real.
 * WebRTC (PeerJS) para o modo multiplayer peer-to-peer.
 * LocalStorage para salvamento de dados locais.
 * JavaScript Moderno (ES6+) puro, sem dependências externas ou frameworks.
