# catdog-and-icecream
#include<iostream>
using namespace std;

int main() {


	char input1;
	char input2;

	cout << "do you like icecream?" << endl;
	cin >> input1;
	cout << "do you like nuts on your ice cream?" << endl;
	cin >> input2;
	
	if (input1 == 'y') {
		if (input2 == 'y')
			cout << " you get postaicho ice cream" << endl;
		else if (input2 == 'n')
			cout << "you get rocky road ice cream" << endl;
	}
	else if (input1 == 'n') {
		if (input2 == 'y')
			cout << "you get a snickers bar" << endl;
		else if (input2 == 'n')
			cout << "you get sketties" << endl;
	}
	else
		cout << " you dont like anything do you boooooooo" << endl;

	char input4;
	char input5;
	char input6;

	cout << "do you like cats or dogs?" << endl;
	cin >> input4;
	cout << "do you like big or small dog?" << endl;
	cin >> input5;
	cout << "do you like long or short hair cats?" << endl;
	cin >> input6;
	
	if (input4 == 'c') {
		if (input6 == 's')
			cout << " you should get a tabby cat" << endl;
		else if (input6 == 'l')
			cout << "you should get a ragdoll cat" << endl;
	}
	else if (input4 == 'd') {
		if (input5 == 'b')
			cout << "you should get a grewat dane " << endl;
		else if (input5 == 's')
			cout << "you should get a tea cup chuala" << endl;
	}
	else
		cout << " you dont like anything do you boooooooo" << endl;






}
