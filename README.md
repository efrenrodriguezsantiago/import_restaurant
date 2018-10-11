/*calcular el importe a pagar por el consumo en un restaurant, tomando en cuenta lo siguiente
- numero de platillos     
- costo por platillos 
se debera calcular el subtotal del consumo, la comision del mesero (5 %)
el iva (0.16 %) y el total a pagar
*/

#include<iostream>
using namespace std;
int main()
{ int n_platillos=0, c_platillos=0,subtotal,comision,iva,subtotalidad,total;

cout<<"\n               introduce el numero de platillos consumidos______________________:";cin>>n_platillos;

cout<<"\n               introduce el costo por platillo__________________________________:";cin>>c_platillos;

subtotal = n_platillos * c_platillos;

cout<<"\n               el subtotal a pagar es___________________________________________:"<<subtotal;

iva = subtotal * 0.16;

cout<<"\n               el iva incluido es_______________________________________________:"<<iva;

comision = (subtotal + iva) * 0.05;

cout<<"\n               la comision del mesero es________________________________________:"<<comision;

total = subtotal +iva + comision;
	
cout<<"\n               el total a pagar es______________________________________________:"<<total;
	
	
	return 0;
}
