#include <iostream>
#include <cstring>
#include <cstdio>

using namespace std;

void compalabra(char palabra[20], char frase[100]);

int main() {
	char palabra[20];
	char frase[100];
	cout<<"Cual es la palabra: "<<endl;
	cin.getline(palabra,20);
	cout<<"Cual es la frase: "<<endl; 
	cin.getline(frase,100);


	compalabra(palabra,frase);
	return 0;
}

void compalabra(char palabra[20], char frase[100]) {
	char aux[20];
	int z=0, cont=1;
	for(int i=0; i<strlen(frase); i++){
	
		aux[z]=frase[i];
		if(isblank(frase[i])){
			aux[z]='\0';
			if(strcmp(aux, palabra)==0)
				cont++;
			z=-1;
		}
	z++;
}
cout<<endl<<"la palabra se repite: "<<cont<<" veces";
	}
