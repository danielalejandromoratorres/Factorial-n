//Factorial n
//Un codigo que calcula el factorial de cualquier numero

#include<stdio.h>
int main(){
 int i, n, aux;
  printf("ingrese el numero que desea factoriar");
  scanf("%d",&n);
  aux=n;
  for(i=1;i<=n;i++){
  	aux=aux*i;
  }
  printf("el factorial de su numero es: %i ", aux);
  
  return 0;
}
