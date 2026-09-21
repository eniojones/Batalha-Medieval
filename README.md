# Pygame - Movimento com Teclado

Exemplo introdutório de desenvolvimento de jogos em Python utilizando a biblioteca **Pygame**. O projeto demonstra a criação de uma janela gráfica, o tratamento do loop principal de eventos e a movimentação contínua de um objeto 2D na tela via teclas direcionais.

## 🚀 Tecnologias

- [Python 3](https://www.python.org/)
- [Pygame](https://www.pygame.org/)

## 🎮 Como Funciona

- **Janela:** Cria uma tela de 800x600 pixels com taxa de atualização contínua.
- **Controles:** Utiliza `pygame.key.get_pressed()` para detectar o pressionamento contínuo das setas:
  - `←` Move para a esquerda
  - `→` Move para a direita
  - `↑` Move para cima
  - `↓` Move para baixo
- **Renderização:** Limpa o fundo para preto a cada frame e desenha um quadrado vermelho de 50x50 pixels na posição calculada.

## ⚙️ Pré-requisitos e Execução

1. Instale o Pygame:
   ```bash
   pip install pygame
