usando-const
============
/* este programa vai calcular o circlo, e depois pular pra uma nova linha.*/


#include<iostream>
using namespace std;

const double pi =3.14159;

const char novalinha = '\n';


int main()


{
    
    double r=5.0;    //raio
    double circlo;


    circlo = 2*pi*r;
    cout << circlo;
    cout << novalinha;

}
