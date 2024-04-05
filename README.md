#include <stdio.h>





float dividirDoisNumeros(float a , float b){
        return a / b;
    }

int solicitarNumero() {
    int numero;
    
    printf("Digite um numero: ");
    scanf("%d", &numero);
    
    return numero;
}

int exibirResultado(int res) {
    printf("O resultado é: %d", res);
}

int main()
{
    int primeiroNumero;
    int segundoNumero;
    int resultado;
    
    primeiroNumero = solicitarNumero();
    segundoNumero = solicitarNumero();
    
    
    resultado = dividirDoisNumeros(primeiroNumero, segundoNumero);

    exibirResultado(resultado);
}
