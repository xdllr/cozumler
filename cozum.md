# cozum1
// ConsoleApplication2.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include "stdio.h"
#include "iostream"

using namespace std;
int main()
{
	int x , y ;
	cout << " X Kordinat Değerlerini Giriniz:";
	cin >> x;
	cout << "Y Kordinat Değerlerini Giriniz:";
	cin >> y;
	
	    int bx = 30 - 10;
		int by = 20 - 10;
		int cx = 20 - 10;
		int cy = 40 - 10;
		int qx = x - 10;
		int qy = y - 10;

		int d = bx*cy - (cx*by);
		int wa = (x*(by - cy) + y*(cy - bx) + bx*cy - cx - by) / d;
		int wb = (x*cy - y*cx) / d;
		int wc = (y*bx - x*by) / d;

		if (0 < wa < 1 && 0 < wb < 1 && 0 < wc < 1)
			cout << "Sonuc:4. nokta ucgenin icinde..";
		else
			cout << "Girilen nokta ücgenin icinde degil..";

		cin>> x;
    return 0;
}

#cozum 2


#include "stdafx.h"
#include "stdio.h"
#include "iostream"

using namespace std;
int main()
{

	int x;
	int z = 1;
	int g = 1;
	int fac = 1;
	cout << "Lutfen Gırıs degerını gırınız..";
	cin >> x;
	
		
	for (int y = 1; y < x+1; y++)
	{
		fac = fac * y;
		cout << fac;
		cout << "  ";
		
		if ( g == z)
		{
			cout << "\n";

			g++;
			z = 0;
		}
		z++;
	}
	cin >> x;
		

	return 0;
}

#cozum3



#include "stdafx.h"
#include "stdio.h"
#include "iostream"
#include <float.h>
#include <limits>

using namespace std;
int main()
{
	DBL_MAX_10_EXP;
	
		double g = 1.115454882121;

	 double x;
     double z = 1.0;
	 double a;

	cout << "Lutfen Gırıs degerını gırınız..";
	cin >> x;
	
	cout << g;

	a = (z + (x / z)) / 2;
	z = a;
	cout << a;
	cout << "		";
	a = (z + (x / z)) / 2;
	z = a;
	cout << a;
	cout << "		";
	a = (z + (x / z)) / 2;
	z = a;
	cout << a;
	cout << "		";
	a = (z + (x / z)) / 2;
	z = a;
	cout << a;
	cout << "		";
	a = (z + (x / z)) / 2;
	z = a;
	cout << a;
	cout << "		";
	a = (z + (x / z)) / 2;
	z = a;
	cout << a;
		
	/*for (int y = 0; y < 5; y++)
	{
		
		a = (z + (x / z)) / 2;
		cout << a;
		cout << "			";
		if (y == 4) {
			cout << a;
		}
		z = a;


	}*/
	cin >> x;
		

	return 0;
}

#cozum4





