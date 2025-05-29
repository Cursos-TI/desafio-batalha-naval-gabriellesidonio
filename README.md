# Desafio Batalha Naval 

Este projeto simula um jogo de Batalha Naval, dividido em três níveis de dificuldade: Novato, Aventureiro e Mestre.

## Objetivo Geral
Simular, em três etapas, a construção de um tabuleiro de Batalha Naval com diferentes níveis, utilizando conceitos fundamentais da linguagem C, como:

- Matrizes (vetores bidimensionais)
- Estruturas de repetição (for, if, etc.)
- Execução de habilidades com padrões.

## Nível Novato
- Posicionamento de dois navios: um na vertical e outro na horizontal.
- Exibição das coordenadas ocupadas no terminal.
- Uso de vetores bidimensionais simples.

## Nível Aventureiro
- Tabuleiro expandido para 10x10.
- Posicionamento de quatro navios, incluindo diagonais.
- Exibição visual de todo o tabuleiro, com 0 (água) e 3 (navio).

## Nível Mestre
A ideia é aplicar habilidades especiais com padrões geométricos no tabuleiro, como se fossem “golpes” com diferentes formatos.

Cada habilidade é representada por uma matriz 5x5 que desenha uma forma: cone, cruz ou octaedro (tipo um losango). Essa forma é usada pra marcar áreas do tabuleiro, como se fossem ataques.

Como funciona
O tabuleiro é uma matriz 10x10, toda preenchida com água (valor 0).Um navio é colocado como exemplo (valor 3).
Depois, a matriz da habilidade (cone, cruz ou octaedro) é sobreposta no tabuleiro.
As células afetadas pela habilidade recebem o valor 5 (se não tiver navio ali).
O centro da habilidade pode ser ajustado, mudando duas variáveis: origemLinha e origemColuna.

Arquivos
cone.c → desenha uma área em formato de cone (triângulo invertido).

cruz.c → desenha uma cruz, com linha e coluna centrais.

octaedro.c → desenha um losango (também chamado de octaedro aqui).

