#include <stdio.h>
#include <locale.h>


float calculo(float sal){
   float perc, valor;

   printf("Informe o Percentual: ");
   scanf("%f",&perc);

   valor = valor * perc/100;
   return valor;

int main(){

setlocale(LC_ALL,"portuguese_brazil");

    float sal, aum, novo_sal;

    printf("Informe o seu salário\n");
    printf("Salário: ");
    scanf("%f",&sal);

    aum = calculo(sal);

    novo_sal = sal + aum;

    printf("O almento foi de R$%.2f resultando no novo Salário de R$%.2f",aum,novo_sal);

    return 0;

}
