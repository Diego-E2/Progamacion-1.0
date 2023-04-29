#include <iostream>
#include <cstdlib>
#include <ProyectoL4.h>
using namespace std;

int main()
{
    int opcion;
    bool repetir = true;
    
    do {
        system("cls");
        
        // Texto del menú que se verá cada vez
        cout << "\n\nMenu de Opciones" << endl;
        cout << "1. Opcion 1" << endl;
        cout << "2. Opcion 2" << endl;
        cout << "3. Opcion 3" << endl;
        cout << "0. SALIR" << endl;
        
        cout << "\nIngrese una opcion: ";
        cin >> opcion;
        
        switch (opcion) {
            case 1:
                // Lista de instrucciones de la opción 1                
                float R;
	
	cout<<"Ingrese el radio: ";
	cin>>R;
	
	cout<<"El area del circulo es: "<< area_circulo (R)<<endl;
	
                system("pause>nul"); // Pausa
                break;
                
            case 2:
                // Lista de instrucciones de la opción 2  
				float L;
	
	cout<<"Ingrese el radio: ";
	cin>>L;
	
	cout<<"El area del cuadrado es: "<< area_cuadrado (L)<<endl;
}              
                
                system("pause>nul"); // Pausa
                break;
                
            case 3:
                // Lista de instrucciones de la opción 3    
				float B, H;
	
	
	cout<<"Ingrese el base: ";
	cin>>B;
	
    cout<<"Ingrese el base: ";
	cin>>H;
	
	cout<<"El area del triangulo es: "<< area_triangulo (B, H) <<endl;            
                
                system("pause>nul"); // Pausa            
                break;
                
            
            case 0:
            	repetir = false;
            	break;
        }        
    } while (repetir);
	 
    return 0;
}
