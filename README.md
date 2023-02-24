# Progamacion-1.0
Aquí se subirán las tareas de la clase 

     //Ejemplo de tarea #1, Uso de "for"
     //Algoritmo de los numeros del 1 al 10
     //Empezamos seleccionando las librerias 
     #include <iostream>
     #include <conio.h>

     //Habilitamos el salto de linea 
     using namespace std; 

     int main(){

     //Declaramos la variable i 
     int i;

     for( i=1; i<=10; i++){
     cout<<i<<endl;
     }
     
     return 0;
     }
     
   .

      //Ejemplo de tarea #1, Uso de "do while"
      /Algoritmo de los numeros del 1 al 20
      //Empezamos seleccionando las librerias 
      #include <iostream>
      #include <conio.h>

       //Habilitamos el salto de linea 
       using namespace std; 

       int main(){
       //Declaramos la variable 
       int i;
       i = 1;
       do{
       cout<<i<<endl;
	  i++;//Aumenta el iterador de uno en uno
       }while(i<=10);

        return 0;
        }
.

       //Ejemplo de tarea #1, Uso de "while"
       //Algoritmo que muestra los numeros del 1 al 10 
       //Empezamos seleccionando las librerias 
       #include <iostream>
       #include <conio.h>

       //Habilitamos el salto de linea 
       using namespace std; 

        int main(){

        //Declaramos la variable i 
        int i;

         i=1;
	
         while(i<=10){
	 cout<<i<<endl;
	
         i ++;	
         }

         return 0;
         }
.

         ////Ejemplo de tarea #1, Uso de "Vector"
         /* Escribir un progrma en donde se defina un vector y que calcule la suma de sus elementos 
         */

         //Empezamos seleccionando las librerias 
          #include <iostream>
         #include <conio.h>

         //Habilitamos el salto de linea 
         using namespace std; 

         int main(){
         int numeros[] = {1,2,3,4,5};
         int suma = 0;

         for(int i=0;i<5;i++){
	 suma += numeros[i];
         }
     
         cout<<"La suma de los numeros del vector es:"<<suma<<endl;


          return 0;
          }
.
