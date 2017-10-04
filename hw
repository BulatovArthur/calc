#include "stdafx.h"
#include <iostream>
#include <conio.h>
#include <locale>

using namespace std;

int main()
{
	setlocale(LC_ALL, "Russian");
	int count;
	double a, b;
	cout << "Введите первое число: ";
	cin >> a;
	cout << "Введите второе число: ";
	cin >> b;
	cout << "Выберите действие:	1-сложение; 2-вычитание; 3-умножение; 4-деление: ";
	cin >> count;
	switch (count)
	{
	case 1:
	{
		cout << a << "+" << b << "=" << a + b << endl;
		break;
	}
	case 2:
	{
		cout << a << "-" << b << "=" << a - b << endl;
		break;
	}
	case 3:
	{
		cout << a << "*" << b << "=" << a * b << endl;
		break;
	}
	case 4:
	{
		cout << a << "/" << b << "=" << a / b << endl;
		break;
	}
	default:
		cout << "Что-то пошло не так, выбирай от 1 до 4!" << endl;
		cin.get();
    _getch();
	return 0;
	}
}
