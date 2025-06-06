
#include <stdio.h>
#include <stdlib.h>

int main() {

    char estado1;
    char state2[4];
    int menu;
    char codigo1[20], codigo2[20];
    char nomecidade1[20], nomecidade2[20];
    int populacao1, populacao2;
    float area1, area2; 
    float pib1, pib2;
    float densidade1, densidade2;    
    int ptsturisticos1, ptsturisticos2;
    float pibper1, pibper2;
    char primeiroatributo, segundoatributo;
    int resultado, resultado2;
    int ch; // declare só uma vez

    printf("Insira os dados da carta 1\n");
    printf("Insira a inicial do estado 1:\n");
    scanf(" %c", &estado1);  // espaço para limpar buffer
    printf("A inicial é: %c\n", estado1);

    printf("Insira o código da carta do estado 1:\n");
    scanf("%s", codigo1);
    printf("O código é: %s\n", codigo1);

    printf("Insira o nome da cidade do estado 1:\n");
    scanf("%s", nomecidade1);
    printf("O nome da cidade é: %s\n", nomecidade1);

    printf("Insira a população do estado 1:\n");
    scanf("%i", &populacao1);
    printf("A população é de: %i\n", populacao1);

    printf("Insira a area do estado 1:\n");
    scanf("%f", &area1);
    printf("A area é de: %f\n", area1);

    printf("Insira o pib do estado 1:\n");
    scanf("%f", &pib1);
    printf("O pib é de: %f\n", pib1);

    printf("Insira a quantidade de pontos turísticos do estado 1:\n");
    scanf("%i", &ptsturisticos1);
    printf("A quantidade de pontos turísticos são de: %i\n", ptsturisticos1);
    
    densidade1 = (float)populacao1 / area1;
    printf("A densidade da população é de: %f\n", densidade1);
    
    pibper1 = pib1 / populacao1;
    printf("O pib per capita é de: %f\n\n", pibper1);

    printf("Insira os dados da carta 2\n");
    printf("Insira a inicial do estado 2:\n");
    scanf(" %s", state2);
    printf("A inicial é: %s\n", state2);

    printf("Insira o código da carta do estado 2:\n");
    scanf("%s", codigo2);
    printf("O código é: %s\n", codigo2);

    printf("Insira o nome da cidade do estado 2:\n");
    scanf("%s", nomecidade2);
    printf("O nome da cidade é: %s\n", nomecidade2);

    printf("Insira a população do estado 2:\n");
    scanf("%i", &populacao2);
    printf("A população é de: %i\n", populacao2);

    printf("Insira a area do estado 2:\n");
    scanf("%f", &area2);
    printf("A area é de: %f\n", area2);

    printf("Insira o pib do estado 2:\n");
    scanf("%f", &pib2);
    printf("O pib é de: %f\n", pib2);

    printf("Insira a quantidade de pontos turísticos do estado 2:\n");
    scanf("%i", &ptsturisticos2);
    printf("A quantidade de pontos turísticos são de: %i\n", ptsturisticos2);

    densidade2 = (float)populacao2 / area2;
    printf("A densidade da população é de: %f\n", densidade2);

    pibper2 = pib2 / populacao2;
    printf("O pib per capita é de: %f\n", pibper2);

    printf("\nEscolha uma opção:\n");
    printf("1. Resultado população\n");
    printf("2. Resultado area\n");
    printf("3. Resultado pib\n");
    printf("4. Resultado densidade\n");
    printf("5. Resultado pontos turísticos\n");
    printf("6. Resultado pib per capita\n");
    scanf("%d", &menu);

    switch (menu) {
        case 1:
            printf("*** RESULTADO ***:\n");
            printf("*** POPULAÇÃO ***:\n");
            if(populacao1 > populacao2){
                printf("Carta 1 ganhou\n");
            } else if (populacao1 < populacao2){
                printf("Carta 2 ganhou\n");
            } else{
                printf("Empate\n");
            }
            break;
        case 2:
            printf("*** ÁREA ***:\n");
            if(area1 > area2){
                printf("Carta 1 ganhou\n");
            } else if (area1 < area2){
                printf("Carta 2 ganhou\n");
            } else{
                printf("Empate\n");
            }
            break;
        case 3:
            printf("*** PIB ***:\n");
            if(pib1 > pib2){
                printf("Carta 1 ganhou\n");
            } else if (pib1 < pib2){
                printf("Carta 2 ganhou\n");
            } else{
                printf("Empate\n");
            }
            break;
        case 4:
            printf("*** DENSIDADE ***:\n");
            if(densidade1 < densidade2){
                printf("Carta 1 ganhou\n");
            } else if (densidade1 > densidade2){
                printf("Carta 2 ganhou\n");
            } else{
                printf("Empate\n");
            }
            break;
        case 5:
            printf("*** PONTOS TURÍSTICOS ***:\n");
            if(ptsturisticos1 > ptsturisticos2){
                printf("Carta 1 ganhou\n");
            } else if (ptsturisticos1 < ptsturisticos2){
                printf("Carta 2 ganhou\n");
            } else{
                printf("Empate\n");
            }
            break;
        case 6:
            printf("*** PIB PER CAPITA ***:\n");
            if(pibper1 > pibper2){
                printf("Carta 1 ganhou\n");
            } else if (pibper1 < pibper2){
                printf("Carta 2 ganhou\n");
            } else{
                printf("Empate\n");
            }
            break;
        default:
            printf("Opção inválida!\n");
            break;
    }

    // Limpar buffer antes da próxima leitura de char
    while ((ch = getchar()) != '\n' && ch != EOF);

    printf("\n\nEscolha um atributo:\n");
    printf("P. Resultado população\n");
    printf("A. Resultado área\n");
    printf("B. Resultado pib\n");
    printf("D. Resultado densidade\n");
    printf("T. Resultado pontos turísticos\n");
    printf("C. Resultado pib per capita\n");
    scanf(" %c", &primeiroatributo);

    switch (primeiroatributo){
        case 'p':
        case 'P':
            printf("Você escolheu população\n");
            resultado = populacao1 > populacao2 ? 1 : 0;
            break;
        case 'A':
        case 'a':
            printf("Você escolheu área\n");
            resultado = area1 > area2 ? 1 : 0;
            break;
        case 'B':
        case 'b':
            printf("Você escolheu pib\n");
            resultado = pib1 > pib2 ? 1 : 0;
            break;
        case 'D':
        case 'd':
            printf("Você escolheu densidade\n");
            resultado = densidade1 < densidade2 ? 1 : 0;
            break;
        case 'T':
        case 't':
            printf("Você escolheu pontos turísticos\n");
            resultado = ptsturisticos1 > ptsturisticos2 ? 1 : 0;
            break;
        case 'C':
        case 'c':
            printf("Você escolheu pib per capita\n");
            resultado = pibper1 > pibper2 ? 1 : 0;
            break;
        default:
            printf("Atributo inválido!\n");
            resultado = -1;
            break;
    }

    // Limpar buffer antes da próxima leitura de char
    while ((ch = getchar()) != '\n' && ch != EOF);

    printf("\n\nEscolha um segundo atributo:\n");
    printf("P. Resultado população\n");
    printf("A. Resultado área\n");
    printf("B. Resultado pib\n");
    printf("D. Resultado densidade\n");
    printf("T. Resultado pontos turísticos\n");
    printf("C. Resultado pib per capita\n");
    scanf(" %c", &segundoatributo);

    if (primeiroatributo == segundoatributo){
        printf("Você escolheu o mesmo atributo\n"); 
    } else {
        switch (segundoatributo) {
            case 'p':
            case 'P':
                printf("Você escolheu população\n");
                resultado2 = populacao1 > populacao2 ? 1 : 0;
                break;
            case 'A':
            case 'a':
                printf("Você escolheu área\n");
                resultado2 = area1 > area2 ? 1 : 0;
                break;
            case 'B':
            case 'b':
                printf("Você escolheu pib\n");
                resultado2 = pib1 > pib2 ? 1 : 0;
                break;
            case 'D':
            case 'd':
                printf("Você escolheu densidade\n");
                resultado2 = densidade1 < densidade2 ? 1 : 0;
                break;
            case 'T':
            case 't':
                printf("Você escolheu pontos turísticos\n");
                resultado2 = ptsturisticos1 > ptsturisticos2 ? 1 : 0;
                break;
            case 'C':
            case 'c':
                printf("Você escolheu pib per capita\n");
                resultado2 = pibper1 > pibper2 ? 1 : 0;
                break;
            default:
                printf("Atributo inválido!\n");
                resultado2 = -1;
                break;
        }

        if (resultado == 1 && resultado2 == 1) {
            printf("Parabéns, você venceu!\n");
        } else if (resultado != resultado2) {
            printf("Empatou!\n");
        } else {
            printf("Infelizmente, você perdeu!\n");
        }
    }

    return 0;
}
