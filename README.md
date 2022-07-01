# Labirinto
Um jogo desenvolvido em C, com interface gráfica no terminal.

## Como rodar o projeto
- Primeiramente deve-se dar o comando "make" no terminal dentro da pasta
- Depois executar o labirinto.exe que está dentro da pasta bin/output.

## Como jogar
O jogador pode escolher entre as dificuldades fácil, médio e difícil, dessa forma caindo com um mapa aleatorio dentre as dificuldades. Então no mapa terá o personagem representado pela letra P, os baus pela letra B, o acampamento pela letra A e a saida pela letra S. Algumas traps invisiveis estão distribuidas pelo mapa também. Você controla o personagem pelas teclas W A S D, fazendo com que se passar pelo bau ira ganhar moedas, se passar pelo acampamento ira ganhar vida, se passar pela saida ira vencer o jogo, e se passar pelas armadilhas invisiveis perderá vida. O objetivo do jogo é conseguir chegar na saida com a maior quantidade de vida, maior quantidade de moedas e menor quantidade de movimentos para fazer o maior score possivel.

## Problemas a serem resolvidos
Após alguns testes, verificamos que o projeto estava rodando corretamente somente em um dos computadores, com SO Linux, com a distro Fedora. E estava rodando parcialmente em SO Linux mas estava com a funcionalidade de salvamento de mapa dando erro de "core dumped". O projeto também não está rodando no windows.
