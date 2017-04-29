//# Practica-1-CPP
//3 Valores tipo FLOAT que se impriman en pantalla

#include <iostream>

using namespace std;

float numb1 = 12.161651616651651651656161;
float numb2 = 2.15616516516515615;
float numb3 = 45.2626626516195165;
float res ;
int main (int argc, char *argv[]) {
	res = numb1 + numb2 + numb3;
	cout <<"PRACTICA 1"<<endl;
	cout <<"Crear 3 variables tipo FLOAT e imprimirlas en pantalla"<<endl;
	cout <<endl;
	cout <<"Valor 1: "<< numb1<<endl ;
	cout <<"Valor 2: "<< numb2<<endl ;
	cout <<"Valor 3: "<< numb3<<endl ;
	cout <<endl;
	cout << "El resultado de la suma de los 3 valores es: "<<' '<<res <<endl ;
	
	return 0;
	
}
