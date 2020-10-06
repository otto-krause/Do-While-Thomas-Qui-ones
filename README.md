# Do-While-Thomas-Qui-ones
Guia_Clase_9

1)
#include<stdio.h >
#include <stdlib.h>


int main()
{
 int a=0;
 while(a<9)
 {
 a=a+1;       
 printf("El contador a vale: %d\n", a);
 }
return 0;
}

2)
#include<stdio.h >
#include <stdlib.h>


int main()
{
 int I=0;
 float Num, NM, Pro,Total; 
 while(I<15)
 {printf("ingrese un numero");
  scanf("%f",&Num);
  Total=Total+Num;
  I=I+1;
  if (Num>NM)
  {
	NM=Num;	 }
 }
 Pro=Total/15;
 printf("El valor promedio es %f\n", Pro);
 printf("El valor mayor %f", NM);
return 0;
}

3)
#include<stdio.h >
#include <stdlib.h>


int main()
{
 int num1=0,num2=0,I;
 printf("Ingrese 2 numeros");
 scanf("%d",&num1);
 scanf("%d",&num2);
 I=num1;
 while(I<num2)
 {  
 printf("%d\n",I);
 I=I+1;
 }
return 0;
}

4)
#include<stdio.h >
#include <stdlib.h>


int main()
{
 int Num=0,F=1,I;
 printf("Ingrese un numero");
 scanf("%d",&Num);
 I=1;
 do
 {  
  F=F*I;
  I=I+1;
 }
 while (I<=Num);
 printf("El factorial es %d\n",F);
return 0;
}

5)
#include<stdio.h >
#include <stdlib.h>


int main()
{
 int Num=0,Num2=0,P=1,I=1;
 printf("Ingrese base");
 scanf("%d",&Num);
 printf("Ingrese exponente");
 scanf("%d",&Num2);
 while(I<=Num2)
 {  
  P=P*Num;
  I++;
 }
 printf("El total es %d\n",P);
return 0;
}

6)
#include<stdio.h >
#include <stdlib.h>


int main()
{
 float N1,N2,N3,N4,N5,N6,N7,N8,N9,N10,ProA,ProG;
 int I,c=0;
 I=1;
 do
 {  
  printf("Ingrese las 10 notas");
  scanf("%f%f%f%f%f%f%f%f%f%f",&N1,&N2,&N3,&N4,&N5,&N6,&N7,&N8,&N9,&N10);
  ProA=(N1+N2+N3+N4+N5+N6+N7+N8+N9+N10)/10;
  printf("el promedio del alumno %d es %f",I,ProA);
  c=c+ProA;
  I=I+1;
 }
 while (I<=30);
 ProG=c/30;
 printf("El promedio de la clase es %f\n",ProG);
return 0;
}

7)
#include <stdio.h>
#include <stdlib.h>


int main()
{
  int i=0,a=1,Num1=0,p=0,U=0,VGen=0;
do
{
    U=0;
    printf ("El vendedor: %d \n",a);
    printf ("Ingresar las unidades vendidas  \n");
    a++;
    i=0;
    p=0;
do
{
    printf (" venta del día  %d\n",i+1);
    scanf ("%d",&U);
    p=p+U;
  if (p > Num1)
        Num1=p;
        i ++;
}
while(i<15);
VGen=VGen+p;
printf ("EL total  de unidades vendidas  del vendedor  %d",a-1);
printf (" es %d \n",p);
       }
while (a<21);
printf("La venta general es %d y la mejor venta es por %d",VGen,Num1);
return 0;
}
8)
#include<stdio.h >
#include <stdlib.h>


int main()
{
 int Num=0,CantP=0,CantN=0,CantC=0,I=1;
 while(I<10)
 {
  printf("Ingrese un numero");
  scanf("%d",&Num);
  I=I+1;
  if (Num>0)
  {
  CantP=CantP+1;
  }
  else
  {
  	if (Num==0)
  	{
	 CantC=CantC+1;
	}
  else
  {
  	CantN=CantN+1;
  }}}
 printf("La cantidad de positivos es %d la de negativos es %d y la de ceros es %d",CantP,CantN,CantC);
return 0;
}

9)
#include<stdio.h >
#include <stdlib.h>


int main()
{
 int Sueldo=0,Cant1=0,Cant2=0,I=0;
 do
 {
  printf("Ingrese el sueldo");
  scanf("%d",&Sueldo);
  I++;
  if (Sueldo>2000)
  {
  Cant1=Cant1+1;
  }
  else
  {
  Cant2=Cant2+1;
  }}
 while(I<20); 
 printf("%d personas ganas más de 2000 y %d personas ganan menos de 2000",Cant1,Cant2);
return 0;
}

