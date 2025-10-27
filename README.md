# algorithm_d_euclide
#include<stdio.h> 
int main () {  
int a, b , i , temp , x , y ;  
printf("saisir le premier nombre :") ;   
scanf("%d",&amp;a);    
printf("saisir le deuxieme nombre :") ;    
scanf("%d",&amp;b);    
x=a ; y=b ;    
while(b!=0) {       
temp=a%b ;      
a=b ;     
b=temp ; } 
printf("le pgcd(%d,%d) est : %d ", x , y , a ) ;   
return 0 ; }
