# tarea1-31-08
/*1.-'include' does not name a type  (include <iostream>)
si se borra el # toma include como una palabra no conocida*/
/*2.-empty file name: (#include <>)
si no se nombra a iostream, que funciona como una libreria que permite el flujo de datos*/
/*3.-#include expect "filename" or <filename> (#include iostream)
sucede al no coloar el nombre entre comillas, lo cual permite que se diferencie*/
/*4.-cout was not declared in this scope  (#include ios)
noreconoce el codigo cout debido a q la libreria a la que pertenece no se ha declarado*/
/*5.-expected '{' before ';' token (namespace std)
si se quita la palabra 'using' no recoce al instrucion para el esapacio de trabajo*/
/*6.-expected identifier before 'int' token (using namespace int;)
no asocia int con namespace*/
/*7.-expected ';' before 'int' (using namespace int)
noidentifica el inicio de la siguiente linea, en la que se espera que este antecdiad por el punto y coma*/
/*8.-main must return 'int (string main())
el tipo para main debe ser de entero*/
/*9.-expected initializer before 'cout' (   cout << "Hello world!" << endl;)
antes de cout debe marcarse un inicio, si se quita la llave no identifica el inicio*/
/*10.-invalid conversion from 'const char*' to 'int' (   return "fin";)
sucede si despues del return se da un valor diferente  un entero, por ejemplo una cadena, la cual no la puede considerar como entero*/

#include <iostream>
using namespace std;
int main()
{
    cout << "Hello world!" << endl;
    return 0;
}
