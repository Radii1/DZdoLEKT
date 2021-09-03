# DZdoLEKT
#include <iostream>
using namespace std;

int main()
{
	setlocale(LC_ALL, "Russian");
	double abric, barsuk, citrus;
	float sum, s1, s2, s3;
	cout << "Добро пожаловать в магазин 'Че по чем', у нас в наличии есть абрикосы по 135руб. за кг, барсучье вяленое мясо по 600руб. за кг, апельсины по 230руб. за кг." << endl;
	cout << "Введите сколько грамм абрикоса желаете взять:";
	cin >> abric;
	cout << endl << "Введите сколько грамм барсучьего вяленого мяса желаете взять:";
	cin >> barsuk;
	cout << endl << "Введите сколько грамм апелисьнов желаете взять:";
	cin >> citrus;
	s1 = 0.135*abric;
	s2 = 0.6*barsuk;
	s3 = 0.23*citrus;
	sum = s1 + s2 + s3;
	cout << endl << "Ваш чек:" << endl << "Абрикос. --- " << abric << "г. === " << s1 << "руб. ";
	cout << endl << "Бар. вял. м. --- " << barsuk << "г. === " << s2 << "руб. ";
	cout << endl << "Апельсин. --- " << citrus << "г. === " << s3 << "руб. ";
	cout << endl << "Всего    ---    " << sum << "руб. ";
	return 0;
}
