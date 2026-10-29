# 🟨 Dash Cube

Um jogo de plataforma de ritmo no estilo Geometry Dash, feito em um único arquivo HTML. Pule espinhos, serras e projéteis, atravesse portais de gravidade e velocidade e complete os 8 mapas, cada um com a sua própria música.

> Sem instalação, sem dependências e sem arquivos de áudio. Abra no navegador e jogue, no PC ou no celular.

## ✨ Recursos

- 8 mapas com dificuldades crescentes, divididos em 2 abas no lobby
- Música original para cada mapa, gerada em tempo real com a Web Audio API (melodia, baixo, arpejos, bateria e eco)
- Menu animado com formas neon que pulsam e tela de ajuda
- Menu de configurações: volume da música, volume dos efeitos, som geral, rastros no chão e apagar recordes
- Obstáculos e mecânicas variados: jump pads, portais de velocidade, portais de gravidade, serras, projéteis e jatos
- Nos mapas da aba 2, jatos e efeitos visuais acompanham a batida da música
- Rastros de poeira no chão, efeito de explosão e som de morte
- Progresso e configurações salvos no aparelho
- Funciona com teclado, mouse e toque

## 🗺️ Mapas

**Aba 1: Clássicos**

| # | Mapa | Dificuldade | Novidade |
|---|------|-------------|----------|
| 1 | Primeiros Passos | Fácil | Jump pads |
| 2 | Neon Rush | Médio | Portais de velocidade |
| 3 | Fogo Cruzado | Difícil | Serras e portais de gravidade |
| 4 | Caos Total | Insano | Tudo junto |

**Aba 2: Ritmo Neon**

| # | Mapa | Dificuldade | Novidade |
|---|------|-------------|----------|
| 5 | Galáxia Pixel | Médio | Projéteis e jatos |
| 6 | Sonhos Elétricos | Difícil | Rajadas de projéteis |
| 7 | Batida Neon | Insano | Gravidade e rajadas |
| 8 | Pulso Final | Lendário | Tudo e projéteis |

## 🧩 Obstáculos

| Elemento | O que faz |
|----------|-----------|
| Espinhos e serras | Matam ao encostar |
| Blocos | Dá para pousar em cima, mas bater de lado mata |
| Pad amarelo | Lança o cubo bem alto |
| Portal laranja / azul | Acelera / volta à velocidade normal |
| Portal roxo | Inverte a gravidade (espinhos no teto) |
| Projétil rápido | Se vier baixo, pule. Se vier alto, não pule |
| Jato vermelho | Só machuca quando está aceso, no ritmo da música |

## 🎮 Controles

| Ação | Teclado | Mouse / Toque |
|------|---------|---------------|
| Pular | `Espaço` ou `↑` (segure para pular de novo ao cair) | Clique / toque na tela |
| Escolher mapa | `1` a `4` (mapas da aba aberta) | Clique / toque no cartão |
| Trocar de aba | `←` / `→` | Toque nos botões das abas |
| Ligar/desligar som | `M` | Configurações |
| Voltar | `Esc` | Botão "Menu" ou "Lobby" |

## 🚀 Como rodar

1. Baixe o arquivo `Dash Cube.html`.
2. Abra no navegador (Chrome, Firefox, Edge ou Safari).
3. Toque em **Jogar**, escolha um mapa e divirta-se.

Para publicar com o **GitHub Pages**, renomeie o arquivo para `index.html`, ative o Pages nas configurações do repositório e compartilhe o link.

> O navegador só libera o áudio depois do primeiro toque ou tecla, então a música começa quando você entra em uma fase.

## 🛠️ Tecnologias

- HTML5 Canvas para os gráficos
- JavaScript puro, sem bibliotecas
- Web Audio API para músicas e efeitos
- `localStorage` para salvar recordes e configurações

## 📌 Ideias futuras

- Skins de cubo
- Mais obstáculos e mecânicas
- Mais mapas e um editor de fases
- Modo de treino com checkpoints

## 📄 Licença

Defina a licença do projeto aqui (por exemplo, MIT).
