## Dino Game
Este é um jogo estilo "Dino Game" desenvolvido em Python com a ajuda de um tutorial do YouTube. O tutorial utilizado como referência foi [Dino Game](https://www.youtube.com/watch?v=OxenBMy13AM&list=PLJ8PYFcmwFOxtJS4EZTGEPxMEo4YdbxdQ&index=15). O jogo utiliza a biblioteca Pygame e foi implementado com base nas instruções do tutorial.

## Pré-requisitos
Certifique-se de ter o Python e a biblioteca Pygame instalados em seu ambiente de desenvolvimento.

```bash
pip install pygame
```

## Como Jogar
1. Execute o arquivo main.py.
2. Pressione a tecla SPACE para fazer o dinossauro pular e evitar obstáculos.
3. Se o dinossauro colidir com um obstáculo, o jogo exibirá "GAME OVER". Pressione r para reiniciar.

## Estrutura do Código

O código está estruturado da seguinte forma:

- main.py: Contém o loop principal do jogo.
- spritesheet.png: Imagem contendo os sprites do dinossauro, cactos, dinossauros voadores e outros elementos.
- sons/: Pasta contendo os sons do jogo.

## Classes Principais

1. Dino: Representa o dinossauro controlado pelo jogador. Possui métodos para pular e atualizar sua posição.
2. Nuvens: Representa as nuvens em movimento no fundo do jogo.
3. Chao: Representa o chão do jogo em movimento.
4. Cacto: Representa um obstáculo cacto que o jogador deve evitar.
5. DinoVoador: Representa um dinossauro voador, outro obstáculo que o jogador deve evitar.

## Agradecimentos

Este projeto foi inspirado nos tutoriais do canal [João Tinti](https://www.youtube.com/@joao-tinti). Agradeço pela inspiração e pelo conhecimento compartilhado.

Desenvolvido por: Mayrton

## Contribuição

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novos recursos. Faça um fork do repositório, crie uma branch para sua feature ou correção e abra um pull request.

## Licença

Este projeto é distribuído sob a licença GNU GENERAL PUBLIC LICENSE. Consulte o arquivo LICENSE.md para obter mais detalhes.
