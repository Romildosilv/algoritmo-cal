# algoritmo-cal
Calculadora Simples//

#include<stdio.h>
float n1,n2,soma;
char op;

int main(){
 printf("****************\n");
 printf("********calculadora");
 printf("\nn1:");
 scanf("%f",&n1);
 printf("\noperacao:+,-,* ou /");
 scanf(" %c",&op);
 printf("\nn2:");
 scanf("%f",&n2);
 switch(op){
 case'+':
  printf("\nsoma = %.2f:",n1+n2);
 break;
 case '-':	
 printf("\nsubtracao = %.2f:",n1-n2);
 break;
 case '*':	
 printf("\nmultiplicacao = %.2f:",n1*n2);
 break;
case '/':
if(n2!=0){
	printf("\ndivisao =%.2f",n1/n2);
}
else{
	printf ("operacao invalida");
	}
	break;
default:
printf("\noperador invalido");
}
	
	
return 0;
}
