#include <iostream>
using namespace std;
int main()
{
    char name[20];
    int mark;
    int age;
    cout << "Kindly Enter  your full name : ";
    cin.getline(name, 20);
    cout << "Kindly Enter your  marks (between 0 - 100): ";
    cin >> mark;
    cout << "Kindly Enter your age:" << endl;
    cin >> age;


    if (mark > 100 || mark < 0) mark = -10;
    switch (mark / 10) {
    case 10:;
    case 9:;
    case 8:cout << "Name: " << name << "\nGrade A\n"; break;
    case 7:cout << "Name: " << name << "\nGrade A\n"; break;
    case 6:cout << "Name: " << name << "\nGrade B\n"; break;
    case 5:cout << "Name: " << name << "\nGrade C\n"; break;
    case 4:cout << "Name: " << name << "\nGrade D\n"; break;
    case 3:;
    case 2:;
    case 1:;
    case 0:cout << "Name: " << name << "\nGrade F\n"; break;
    default: cout << "Invalid marks\n";
    }
    return 0;
}


