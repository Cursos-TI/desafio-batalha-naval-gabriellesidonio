# Nível Aventureiro

Aqui o tabuleiro continua 10x10, mas os navios podem ser posicionados também em diagonais principais e secundárias, além das posições horizontais e verticais. Ainda usamos o 0 para água e 3 para navios.

## Funcionalidades:

* Inicialização do tabuleiro com água.
* Posicionamento de navios horizontais, verticais e diagonais (principal e secundária).
* Impressão do tabuleiro com os navios posicionados.

## Objetivo:
Aprender manipulação de matrizes mais complexas e trabalhar com posicionamentos diagonais usando loops.

## Conceitos utilizados
- Matrizes e vetores
- Navios em posições diagonais (tabuleiro[i][i], tabuleiro[i][9 - i])
- Validação de limites
- Estruturas de repetição

## Como compilar e executar no terminal

cd BatalhaAventureiro
gcc aventureiro.c -o aventureiro
./aventureiro
