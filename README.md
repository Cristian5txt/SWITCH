#include <iostream>

using namespace std;

int main()
{
char dia;
char seguir;
char Y;
char N;
cout<< "INGRESE EL DIA DE LA SEMANA"<<endl;
cin>>dia;

do{
switch (dia){
case 'L' :
cout<< "ACCIONES DEL LUNES SON: "<<endl;
cout<< "ASISTIR A FUND.PROGRAMACION"<<endl;
cout<< "ASISTIR A CALCULO DIFERENCIA Y INTEGRAL"<<endl;
cout<< "ASISTIR A QUIMICA"<<endl;
break;
case 'M':
cout<< "ACCIONES DEL MARTES SON: "<<endl;
cout<< "ASISTIR A BIOLOGIA"<<endl;
cout<< "ASISTIR A ALGEBRA LINEAL"<<endl;
cout<< "ASISTIR A MIC"<<endl;
break;
case 'C':
cout<< "ACCIONES DEL MIERCOLES SON:"<<endl;
cout<< "ASISTIR A FUND.PROGRAMACION"<<endl;
cout<< "ASISTIR A CALCULO DIFERENCIA Y INTEGRAL"<<endl;
cout<< "ASISTIR A QUIMICA"<<endl;
break;
case 'J':
cout<< "ACCIONES DEL JUEVES SON: "<<endl;
cout<< "ASISTIR A BIOLOGIA"<<endl;
cout<< "ASISTIR A ALGEBRA LINEAL"<<endl;
cout<< "ASISTIR A MIC"<<endl;
break;
case 'V':
cout<< "ACCIONES DEL VIERNES SON: "<<endl;
cout<< "ASISTIR A FUND.PROGRAMACION"<<endl;
cout<< "ASISTIR A CALCULO DIFERENCIA Y INTEGRAL"<<endl;
cout<< "ASISTIR A QUIMICA"<<endl;
break;
case 'S':
cout<< "ACCIONES DEL SABADO SON: "<<endl;
cout<< "ESTUDIAR Y REALIZAR DEBERES"<<endl;

break;
case 'D':
cout<< "ACCIONES DEL DOMINGO SON: "<<endl;
cout<< "ESTUDIAR Y REALIZAR DEBERES"<<endl;

break;
    }
cout<< "DESEA ESCOGER OTRO DIA "<<endl;
cout<< " Y ES SI"<<endl;
cout<< "N ES NO"<<endl;
cin
    }while (seguir==Y);
    return 0;
}
