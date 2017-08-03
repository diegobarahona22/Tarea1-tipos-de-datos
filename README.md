# Tarea1-tipos-de-datos
#include <iostream>
#include <limits.h>
#include <float.h>


using namespace std;


int main()
{

    int n, opcion;

    do
    {    /* MENU */
        cout << "\n ======== MENU==========";
        
        cout << "\n   1. Minimo y maximo de char:";
        cout << "\n   2. Minimo y maximo de short int:";
        cout << "\n   3. Minimo y maximo de int:";
        cout << "\n   4. Minimo y maximo de Long int:";
        cout << "\n   5. Minimo y maximo de unsigned char:";
        cout << "\n   6. Minimo y maximo de unsigned short int:";
        cout << "\n   7. Minimo y maximo de unsigned int:";
        cout << "\n   8. Minimo y maximo de unsigned Long int:";
        cout << "\n   9. Minimo y maximo de float:";
        cout << "\n   10. Minimo y maximo de double:";
        cout << "\n   11. Minimo y maximo de Long double:";        
        cout <<"\n   12. Salir.";
        cout <<"\n\n   Introduzca opcion (1-12): ";

        cin>> opcion ;

        /* Inicio */

        switch ( opcion )
        {
            case 1: cout<<"\n"<<"Minimo y maximo de \"char\" ...: "<<"MIN:"<<CHAR_MIN<< "   MAX:"<< CHAR_MAX<<endl; break;

            case 2: cout<<"\n"<<"Minimo y maximo de \"short int\" ...: "<<"MIN:"<<SHRT_MIN<< "   MAX:"<< SHRT_MAX<<endl; break;

            case 3: cout<<"\n"<<"Minimo y maximo de \"int\" ...: "<<"MIN:"<<INT_MIN<< "   MAX:"<< INT_MAX<<endl; break;
                    
            case 4: cout<<"\n"<<"Minimo y maximo de \"long int\" ...: "<<"MIN:"<<LONG_MIN<< "   MAX:"<< LONG_MAX<<endl; break;
            
            case 5: cout<<"\n"<<"Minimo y maximo de \"unsigned char\" ...: "<<"MIN:"<<"0"<< "   MAX:"<< UCHAR_MAX<<endl; break;
            
            case 6: cout<<"\n"<<"Minimo y maximo de \"unsigned short int\" ...: "<<"MIN:"<<"0"<< "   MAX:"<< USHRT_MAX<<endl; break;
                    
            case 7: cout<<"\n"<<"Minimo y maximo de \"unsigned int\" ...: "<<"MIN:"<<"0"<< "   MAX:"<< UINT_MAX<<endl; break;
                    
            case 8: cout<<"\n"<<"Minimo y maximo de \"unsigned Long int\" ...: "<<"MIN:"<<"0"<< "   MAX:"<< ULONG_MAX<<endl; break;
            
            case 9: cout<<"\n"<<"Minimo y maximo de \"float\" ...: "<<"MIN:"<<FLT_MIN<< "   MAX:"<< FLT_MAX<<endl; break;
                    
            case 10: cout<<"\n"<<"Minimo y maximo de \"double\" ...: "<<"MIN:"<<DBL_MIN<< "   MAX:"<< DBL_MAX<<endl; break;
                    
            case 11: cout<<"\n"<<"Minimo y maximo de \"long double\" ...: "<<"MIN:"<<LDBL_MIN<< "   MAX:"<< LDBL_MAX<<endl; break;
         }

         /* Fin */

    } while ( opcion != 12 );

    return 0;
}
