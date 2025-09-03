#include <stdio.h>

#define TAMANHO_TABULEIRO 10

int main() {
    // Inicializa o tabuleiro com zeros (indicando ausência de navios)
    int tabuleiro[TAMANHO_TABULEIRO][TAMANHO_TABULEIRO] = {0};

    // Posiciona o navio horizontal (linha 2, colunas 3 a 5)
    for (int coluna = 3; coluna <= 5; coluna++) {
        tabuleiro[2][coluna] = 1;
    }

    // Posiciona o navio vertical (coluna 7, linhas 5 a 6)
    for (int linha = 5; linha <= 6; linha++) {
        tabuleiro[linha][7] = 1;
    }

    // Exibe as coordenadas do navio horizontal
    printf("Navio horizontal:\n");
    for (int coluna = 3; coluna <= 5; coluna++) {
        printf("(%d,%d)\n", 2, coluna);
    }

    // Exibe as coordenadas do navio vertical
    printf("Navio vertical:\n");
    for (int linha = 5; linha <= 6; linha++) {
        printf("(%d,%d)\n", linha, 7);
    }

    return 0;
}
