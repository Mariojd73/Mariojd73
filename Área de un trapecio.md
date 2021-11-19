
#include<stdio.h>

int main()
{
//Se declaran las variables que se utilizaran
float base_M,base_m,altura,area;

//Introducción de datos por parte de el usuario
printf("Digite la base Mayor: ");
scanf("%f",&base_M);
printf("\nDigite la base menor: ");
scanf("%f",&base_m);
printf("\nDigite la altura: ");
scanf("%f",&altura);

//fórmula para sacar el área 
area=((base_M+base_m)*altura)/2;

//Impresión de datos en pantalla
printf("\nSu área es: %.2f cm2",area);   
printf("\n");   

   return 0;
//Finalización de el programa
}
