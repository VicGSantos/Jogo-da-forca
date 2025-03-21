# Jogo da Forca

O **Jogo da Forca** é uma implementação simples do clássico jogo da forca em Python. O jogo escolhe uma palavra aleatória de uma lista de categorias (animais, comidas, roupas e cores) e o jogador precisa adivinhar as letras da palavra, tentando evitar perder todas as vidas.

## Como Jogar

1. O jogo seleciona aleatoriamente uma palavra de uma das quatro categorias: **animal**, **comida**, **roupa** e **cor**.
2. O jogador tem 8 tentativas para acertar as letras da palavra escolhida.
3. Cada vez que o jogador erra uma letra, ele perde uma vida.
4. O jogo continua até que o jogador acerte a palavra ou perca todas as vidas.

### Regras:
- O jogador pode digitar uma letra por vez.
- Se o jogador digitar algo que não seja uma letra ou mais de uma letra, o jogo avisa para tentar novamente.
- O jogo termina quando o jogador ganha (acertando a palavra) ou perde todas as suas vidas.

## Como Executar

Para rodar o jogo no seu computador, basta seguir os seguintes passos:

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/seu-usuario/jogo-da-forca.git
