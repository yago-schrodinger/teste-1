## licao basica sobre C  sobre como calcular 10 hipotenusas

#include <stdio.h>
#include <math.h>

int main() {
    float cateto1, cateto2, hipotenusa;

    // repeticao dos triangulos
    for (int i = 1; i <= 10; i++) {
        printf("\n--- Triangulo %d ---\n", i);

        printf("Digite o valor do primeiro cateto: ");
        scanf("%f", &cateto1);

        printf("Digite o valor do segundo cateto: ");
        scanf("%f", &cateto2);

        // Teorema de Pitágoras
        hipotenusa = sqrt((cateto1 * cateto1) + (cateto2 * cateto2));

        printf("A hipotenusa do triangulo %d e: %.2f\n", i, hipotenusa);
    }

    return 0;
}
