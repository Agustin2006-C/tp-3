#include<bits/stdc++.h>

using namespace std;

int EsMayor(int a, int b, int c);

int main(){
	
	int a, b, c;
	
	cout<<"Ingrese tres numeros: ";
	cin>>a>>b>>c;
	
	cout<<"El mayor es: "<<EsMayor(a, b, c)<<endl;
	
	return 0;
}

int EsMayor(int a, int b, int c){
	
	int mayor;
	
		if(a > b && a > c){
			mayor = a;
		}
		if(b > c && b > a){
			mayor = b;
		}
		if(c > b && c > a){
			mayor = c;
		}
	return mayor;
}
