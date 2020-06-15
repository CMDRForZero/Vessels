#include <iostream>

using namespace std;

struct notebook1
{
	char model[20];

	short screen;

	int price;

	int dimensions;

	double iron; //в данном случае "iron" - мощность

};

#pragma pack(push,4)

struct notebook2
{

	char model[20];

	short screen;

	int price;

	int dimensions;

	double iron;

};


#pragma pack(pop)
struct notebook3 
{
double iron;

int price;

short screen;

char model[20];

int dimensions;

};

int main()

{

	notebook1 game1;

	cout << "char:" << " " << &game1.model << endl;

cout << "short" << " " << &game1.screen << endl;

	cout << "int:" << " " << &game1.price << endl;

	cout << " int:" << " " << &game1.dimensions << endl;

	cout << " double:" << " " << &game1.iron << endl;

	cout << "Sum of bites of data:" << " " << sizeof(game1.model) + sizeof(game1.screen) + sizeof(game1.price) + sizeof(game1.dimensions) + sizeof(game1.iron) << " " << "bites" << endl;

	cout << "Size of stuct:" << " " << sizeof(notebook1) << "bites" << endl;

	notebook2 game2;

	cout << "char:" << " " << &game2.model << endl;

	cout << "short" << " " << &game2.screen << endl;

	cout << "int:" << " " << &game2.price << endl;

	cout << " int:" << " " << &game2.dimensions << endl;

	cout << " double:" << " " << &game2.iron << endl;

		cout << "Sum of bites of data:" << " " << sizeof(game2.model) + sizeof(game2.screen) + sizeof(game2.price) + sizeof(game2.dimensions) + sizeof(game2.iron) << " " << "bites" << endl;

	cout << "Size of stuct:" << " " << sizeof(notebook2) << "bites" << endl;

	notebook3 game3;

	cout << "char:" << " " << &game3.model << endl;

	cout << "short" << " " << &game3.screen << endl;

	cout << "int:" << " " << &game3.price << endl;

	cout << " int:" << " " << &game3.dimensions << endl;

	cout << " double:" << " " << &game3.iron << endl;

	cout << "Sum of bites of data:" << " " << sizeof(game3.model) + sizeof(game3.screen) + sizeof(game3.price) + sizeof(game3.dimensions) + sizeof(game3.iron) << " " << "bites" << endl;

	cout << "Size of stuct:" << " " << sizeof(notebook3) << "bites" << endl;

	return 0;
}
