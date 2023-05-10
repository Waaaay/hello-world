# include <iostream>
using namespace std;
int main()
{
	setlocale(LC_ALL, "Russian");
	double sum = 0, a[10], kol = 0;
	cout << "Введите числа:" << endl;
	for (int i = 0; i < 10; i++) {
		cin >> a[i];
	}
	for (int i = 0; i < 10; i++)
	{
		if ((a[i] >= -1) && (a[i] <= 0)) sum = sum + a[i];
		if (a[i] >= (1.5)) kol = kol + 1;
	}
	cout << "Количество чисел, больших или равных 1,5 = " << kol << endl;
	cout << "Сумма отрицательных чисел, входящих в диапазон [-1..0] = " << sum;
}
