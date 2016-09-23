# Panel Solar

#include <iostream>

using namespace std;

int main()
{
	int Sol, Mercurio, Venus, Tierra, Marte, Jupiter, Saturno, Neptuno, Urano, planeta;
	Sol = 0;
	Mercurio = 1;
	Venus = 2;
	Tierra = 3;
	Marte = 4;
	Jupiter = 5;
	Saturno = 6;
	Urano = 7;
	Neptuno = 8;

	cout << "Fuerza Total de un planeta" << endl;
	cout << "Cual planeta quiere saber?" << "\n" << "Mercurio = 1" << "\n" << "Venus = 2" << "\n" << "Tierra = 3" << "\n" << "Marte = 4" << "\n" << "Jupiter = 5" << "\n" << "Saturno = 6" << "\n" << "Urano = 7" << "\n" << "Neptuno = 8" << endl;
	cin >> planeta;
	if (planeta != 1 && planeta != 2 && planeta != 3 && planeta != 4 && planeta != 5 && planeta != 6 && planeta != 7 && planeta != 8)
	{
		cout << "En que sistema solar vives, XD" << endl;
	}
	else
	{
		if (planeta == 1)
		{
			cout << "El planeta escogido es: Mercurio" << "\n" << "Informacion Basica de Mercurio" << "\n" << "Diametro = 4.878 Km" << "\n" << "Distancia media al Sol = 58'344.000 Km" << "\n" << "Periodo de rotacion = 58,6 dias" << "\n" << "Periodo de revolucion = 87,9 dias" << "\n" << "Masa = 3,285 x 10^23 Kg" << endl;
			cout << "\n" <<"Distancia media de cada planeta a Mercurio" << "\n" << "Venus = 49'368.000 Km" << "\n" << "Tierra = 91'256.000 Km" << "\n" << "Marte =  Km" << "\n" << "Jupiter =  Km" << "\n" << "Saturno =  Km" << "\n" << "Urano =  Km" << "\n" << "Neptuno =  Km" << endl;
		}
		if (planeta == 2)
		{
			cout << "El planeta escogido es: Venus" << "\n" << "Informacion Basica de Venus" << "\n" << "Diametro = 12.100 Km" << "\n" << "Distancia media al Sol = 107'712.000 Km" << "\n" << "Periodo de rotacion = 243 dias" << "\n" << "Periodo de revolucion = 224,7 dias" << "\n" << "Masa = 4,869 x 10^24 Kg" << endl;
			cout << "Distancia media de cada planeta a Venus" << "\n" << "Mercurio =  Km" << "\n" << "Tierra =  Km" << "\n" << "Marte =  Km" << "\n" << "Jupiter =  Km" << "\n" << "Saturno =  Km" << "\n" << "Urano =  Km" << "\n" << "Neptuno =  Km" << endl;
		}
		if (planeta == 3)
		{
			cout << "El planeta escogido es: Tierra" << "\n" << "Informacion Basica de Tierra" << "\n" << "Diametro = 12.756 Km" << "\n" << "Distancia media al Sol = 149'600.000 Km" << "\n" << "Periodo de rotacion = 23,9 horas" << "\n" << "Periodo de revolucion = 365,6 dias" << "\n" << "Masa = 5,9736 x 10^24 Kg" << endl;
			cout << "Distancia media de cada planeta a Tierra" << "\n" << "Mercurio =  Km" << "\n" << "Venus =  Km" << "\n" << "Marte =  Km" << "\n" << "Jupiter =  Km" << "\n" << "Saturno =  Km" << "\n" << "Urano =  Km" << "\n" << "Neptuno =  Km" << endl;
		}		
		if (planeta == 4)
		{
			cout << "El planeta escogido es: Marte" << "\n" << "Informacion Basica de Marte" << "\n" << "Diametro = 6.787 Km" << "\n" << "Distancia media al Sol = 227'392.000 Km" << "\n" << "Periodo de rotacion = 24,6 horas" << "\n" << "Periodo de revolucion = 686,9 dias" << "\n" << "Masa = 6,4185 x 10^23 Kg" << endl;
			cout << "Distancia media de cada planeta a Marte" << "\n" << "Mercurio =  Km" << "\n" << "Venus =  Km" << "\n" << "Tierra =  Km" << "\n" << "Jupiter =  Km" << "\n" << "Saturno =  Km" << "\n" << "Urano =  Km" << "\n" << "Neptuno =  Km" << endl;
		}		
		if (planeta == 5)
		{
			cout << "El planeta escogido es: Jupiter" << "\n" << "Informacion Basica de Jupiter" << "\n" << "Diametro = 142.984 Km" << "\n" << "Distancia media al Sol = 777'920.000 Km" << "\n" << "Periodo de rotacion = 9,8 horas" << "\n" << "Periodo de revolucion = 11,8 años" << "\n" << "Masa = 1,899 x 10^27 Kg" << endl;
			cout << "Distancia media de cada planeta a Jupiter" << "\n" << "Mercurio =  Km" << "\n" << "Venus =  Km" << "\n" << "Tierra =  Km" << "\n" << "Marte =  Km" << "\n" << "Saturno =  Km" << "\n" << "Urano =  Km" << "\n" << "Neptuno =  Km" << endl;
		}		
		if (planeta == 6)
		{
			cout << "El planeta escogido es: Saturno" << "\n" << "Informacion Basica de Saturno" << "\n" << "Diametro = 120.536 Km" << "\n" << "Distancia media al Sol = 1'427'184.000 Km" << "\n" << "Periodo de rotacion = 10,6 horas" << "\n" << "Periodo de revolucion = 29,4 años" << "\n" << "Masa = 5,688 x 10^26 Kg" << endl;
			cout << "Distancia media de cada planeta a Saturno" << "\n" << "Mercurio =  Km" << "\n" << "Venus =  Km" << "\n" << "Tierra =  Km" << "\n" << "Marte =  Km" << "\n" << "Jupiter =  Km" << "\n" << "Urano =  Km" << "\n" << "Neptuno =  Km" << endl;
		}		
		if (planeta == 7)
		{
			cout << "El planeta escogido es: Urano" << "\n" << "Informacion Basica de Urano" << "\n" << "Diametro = 51.108 Km" << "\n" << "Distancia media al Sol = 2'870'824.000 Km" << "\n" << "Periodo de rotacion = 17,2 horas" << "\n" << "Periodo de revolucion = 84 años" << "\n" << "Masa = 8,686 x 10^25 Kg" << endl;
			cout << "Distancia media de cada planeta a Urano" << "\n" << "Mercurio =  Km" << "\n" << "Venus =  Km" << "\n" << "Tierra =  Km" << "\n" << "Marte =  Km" << "\n" << "Jupiter =  Km" << "\n" << "Saturno =  Km" << "\n" << "Neptuno =  Km" << endl;
		}
		if (planeta == 8)
		{
			cout << "El planeta escogido es: Neptuno" << "\n" << "Informacion Basica de Neptuno" << "\n" << "Diametro = 49.538 Km" << "\n" << "Distancia media al Sol = 4'496'976.000 Km" << "\n" << "Periodo de rotacion = 16 horas" << "\n" << "Periodo de revolucion = 164,8 años" << "\n" << "Masa = 1,024 x 10^26 Kg" << endl;
			cout << "Distancia media de cada planeta a Neptuno" << "\n" << "Mercurio =  Km" << "\n" << "Venus =  Km" << "\n" << "Tierra =  Km" << "\n" << "Marte =  Km" << "\n" << "Jupiter =  Km" << "\n" << "Saturno =  Km" << "\n" << "Urano =  Km" << endl;
		}
	}
    return 0;
}

