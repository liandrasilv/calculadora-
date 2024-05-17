#include <stdio.h>
int. mult, soma, sub;
float div;

void soma();
void multiplicação();
void subtração();
void divisão();

int main(){
    int op;
    printf("Digite 1 para soma:");
    printf("Digite 2 para mult:");
    printf("Digite 3 para sub:");
    printf("Digite 4 para div:");
    scanf("%d" &op);
    if (op==1){
        soma();
    }
    if (op==2){
        mult();

    }
    if(op==3){
        sub();
    }
    if(op==4){
        div();
    }
    return 0;
}

void soma(){
int n1,n2;
printf("digite o primeiro numero:");
scanf( "%d" &n1);
printf("digite o segundo numero:");
scanf("%d" &n2);

int soma = (n1 + n2);

printf("a soma é: %d", soma)
{

void multiplicação(){

int n1,n2;
printf("digite o primeiro numero:");
scanf( "%d" &n1);
printf("digite o segundo numero:");
scanf("%d" &n2);

int mult = (n1 * n2);

printf("a multiplicação é: %d", multiplicação)
{

void subtração(){

int n1,n2;
printf("digite o primeiro numero:");
scanf( "%d" &n1);
printf("digite o segundo numero:");
scanf("%d" &n2);

int sub = (n1 - n2);

printf("a subtração é: %d", subtração)
{

void divisão(){

int n1,n2;
printf("digite o primeiro numero:");
scanf( "%d" &n1);
printf("digite o segundo numero:");
scanf("%d" &n2);

float soma = (n1/n2);

printf("a divisão é: %2f", divisão)
{
