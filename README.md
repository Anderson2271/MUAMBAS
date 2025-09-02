#include <stdio.h>
#include <string.h>


struct Estado {
    char nome[20];
    char codigo[5];
    char capital[20];
    long popupalaçao;
    double area;
    long long pib;
    int pontos_turisticos;
};

struc Estado baralho[2];
// Funçao para inicializar o baralho 
void inicializarBaralho() {
    // Carta 1: São Paulo
    strcpy(baralho[0].nome, "São Paulo");
    strcpy(baralho[0].codigo, "SP");
    strcpy(baralho[0].capital, "São Paulo");
    baralho[0].população = 44800000;
    baralho[0].area = 248222.8;
    baralho[0].pib = 2200000000000;
    baralho[0].pontos_turisticos = 200

 strcpy(baralho[1].nome, "Rio de Janeiro");
 strcpy(baralho[1].codigo, "RJ");
 strcpy(baralho[1].capital, Rio de Janeiro");
 baralho[1].população = 17600000;
 baralho[1].area = 44000.1;
 baralho[1].pib = 900000000000;
 baralho[1].pontos_turisticos = 150;
    
}

void exibirCarta(struct Estado carta) {
    printf("----------------------\n");
    printf("São Paulo: %s\n",carta.nome);
    printf("SP: %s\n",carta.codigo);
    printf("Capital: %s\n",carta.capital);
    printf("População: %ld\n",carta.população);
    printf("Area (km2): %.2f\n",carta.area);
    printf("PIB (R$): %lld\n",carta.pib);
    printf("Pontos Turisticos: %d\n",carta.pontos_turisticos);
    printf("---------------------------------------\n");
    
    
}
    
int main() {
    inicializarBaralho();
    printf("Carta 1:\n");
    exibirCarta(baralho[0]);
    printf("\nCarta 2:\n");
    exibirCarta(baralho[1]);

return 0

}    




































    
 






}
