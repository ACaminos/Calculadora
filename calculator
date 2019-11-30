#include <stdio.h>
#include <stdlio.h>

int main () {
Float a,b,d;
int c;
printf("¡Bienvenido!\n");
printf("Por favor, ingrese un número: \n");
scanf("%f,&a);
printf("Por favor, ingrese el segundo número: \n");
scanf("%f,&b);
printf("¿Que operación desea realizar?\n 1- Suma\n2-Resta\n3-Multiplicación\n4-División\n");
scanf("%d",&c);
do{
switch(c){
    case 1:
            d=a+b;
            printf("Usted ha elegido la opción SUMA. El resultado es : %f\n",d);
            break;
    case 2:
            d=a-b;
            printf("Usted ha elegido la opción RESTA. El resultado es: %f\n",d);
            break;
    case 3:
            d=a*b;
            printf("Usted ha elegido la opción MULTIPLICACIÓN. El resultado es: %f\n",d);
            break;
    case 4:
            d=a/b;
            if(b==0)
                      {
                      printf("No se puede dividir por 0. Error");
                      }
                      else
                      {
                      printf("Usted ha elegido la opción DIVIDIR. El resultado es: %.2f\n",d);
                      }
            break;
    default:
            printf("Por favor vuelva a ingresar un numero dentro de los parametros establecidos...");
            break;
            }
while (c<= 0 || c>=5);

System("PAUSE");
return 0;

}
