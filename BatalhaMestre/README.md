# Nível Mestre

O desafio Mestre divide o código em três partes, cada uma em arquivos separados: cone.c, cruz.c e octaedro.c. Cada arquivo cria uma matriz de habilidade especial (cone, cruz, losango) que representa uma área de efeito sobre o tabuleiro.

## Funcionalidades comuns:

* Inicialização do tabuleiro com água (0).
* Posicionamento de navios para testes visuais.
* Criação da matriz de habilidade (cone, cruz ou losango) em uma matriz 5x5.
* Sobreposição da matriz de habilidade no tabuleiro respeitando os limites.
* Marcação da área de habilidade com o número 5 no tabuleiro.
* Impressão do tabuleiro final com navios (3) e área de habilidade (5).

## Arquivos:

- cone.c: habilidade com formato de cone, expandindo em largura a cada linha.
- cruz.c: habilidade em formato de cruz, linhas e colunas centrais ativas.
- octaedro.c: habilidade em formato de losango, definida pela distância de Manhattan.

## Objetivo:
Desenvolver habilidades avançadas de manipulação de matrizes, uso de lógica para áreas geométricas e sobreposição de matrizes dentro de limites.

## Conceitos utilizados
- Matrizes 2D
- Estruturas condicionais com loops aninhados
- Sobreposição de matrizes de habilidade no tabuleiro

## Como compilar e executar

cd BatalhaMestre
gcc cone.c -o cone && ./cone
gcc cruz.c -o cruz && ./cruz
gcc octaedro.c -o octaedro && ./octaedro