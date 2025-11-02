#include<iostream>
#include<cmath>
using namespace std;
int main()
{
	int num, a, b, c;
	cout << "pleaze enter a number consist os three digits to print each digit on a separate line." << endl;
	cin >> num;
	if (num < 100 || num>900)
	{
		cout << "The number does not consist of three digits." << endl;
		return 1;
	}

	// Read intrgers in different way
	a = num / 100; // first digit
	b = (num - a * 100) / 10; //second digit
	c = num - a * 100 - b * 10; //third digit

	cout << a << endl;
	cout << b << endl;
	cout << c << endl;

	return 0; 
	
}
