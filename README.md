#include <iostream.h>
#include <conio.h>

void main()
{
	char doc[9][5] = { "mot", "hai", "ba", "bon", "nam", "sau", "bay", "tam", "chin" };
	int van, ngan, tram, chuc, donvi, chv, dv;
	long so;
	clrscr();

	cout << "Nhap so nguyen duong < 1000000 can doc = ";
	cin >> so;
	cout << "Cach doc so " << so << " la:\n";
#include <stdio.h>
#include <conio.h>
#include <math.h>

void main()
{
	float a, b, c, d;
	clrscr();
	printf("Nhap cac he so a, b, c : ");
	scanf("%f%f%f", &a, &b, &c);
	if (a)
	{
		d = b *b - 4 *a * c;
		if (d < 0) printf("Vo nghiem !");
		if (d == 0) printf("Nghiem kep x=%4.2f", -0.5 *b / a);
		if (d > 0)
		{
			printf("Hai nghiem phan biet :\n");
			printf("x1=%4.2f", 0.5 *(-b - sqrt(d)) / a);
			printf(" x2=%4.2f", 0.5 *(-b + sqrt(d)) / a);
		}
	}
	else if (b) printf("Mot nghiem x=%4.2f", -c / b);
	else if (c) printf("Vo nghiem !");
	else printf("Vo so nghiem !");
	getch();
}
	van = so / 10000;
	ngan = so / 1000 % 10;
	tram = so / 100 % 10;
	chuc = so / 10 % 10;
	donvi = so % 10;

	if (van)
	{
		chv = van / 10;
		dv = van % 10;
		if (chv == 1)
			cout << "muoi ";
		else if (chv > 1)
			cout << doc[chv - 1] << " muoi ";
		if (dv)
			cout << doc[dv - 1];
		cout << " van ";
	}

	if ((ngan == 0) && van)
		cout << " khong ngan ";
	else if (ngan)
		cout << doc[ngan - 1] << " ngan ";
#include <stdio.h>
#include <conio.h>
#include <math.h>

void main()
{
	float a, b, c, d;
	clrscr();
	printf("Nhap cac he so a, b, c : ");
	scanf("%f%f%f", &a, &b, &c);
	if (a)
	{
		d = b *b - 4 *a * c;
		if (d < 0) printf("Vo nghiem !");
		if (d == 0) printf("Nghiem kep x=%4.2f", -0.5 *b / a);
		if (d > 0)
		{
			printf("Hai nghiem phan biet :\n");
			printf("x1=%4.2f", 0.5 *(-b - sqrt(d)) / a);
			printf(" x2=%4.2f", 0.5 *(-b + sqrt(d)) / a);
		}
	}
	else if (b) printf("Mot nghiem x=%4.2f", -c / b);
	else if (c) printf("Vo nghiem !");
	else printf("Vo so nghiem !");
	getch();
}
	if ((tram == 0) && (van || ngan))
		cout << " khong tram ";
	else if (tram)
		cout << doc[tram - 1] << " tram ";

	if ((chuc == 0) && donvi && (van || ngan || tram))
		cout << "le ";
	else if (chuc == 1)
		cout << " muoi ";
	else
		cout << doc[chuc - 1] << " muoi ";
	if (donvi)
		cout << doc[donvi - 1];
	getch();
}# hgreg
