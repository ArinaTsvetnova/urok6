#include <iostream>
#include <string>
using namespace std;
int main ()
{

    //Задание 1
    string d = "Hel", e = "lo", f = "p";
    f = d + e;
    cout << "d + e = " << f << endl;
    int a = 6, b = 4, c = 0, j = 0, h = 2, i = 0;
    c = a - b;
    cout << "a - b = " << c << endl;
    j = a * b;
    cout << "a * b = " << j << endl;
    h = a / h;
    cout << "a / h = " << h << endl;
    i = a % b;
    cout << "a % b = " << i << endl;
    
    //Задание 2
    cout << boolalpha;
    int a1 = 0, b1 = 0, c1 = 1, d1 = 1, e1 = 2;
    cout << "true = " << (a1 == b1) << endl;
    cout << "false = " << (a1 == c1) << endl;
    cout << "true = " << (a1 != c1) << endl;
    cout << "false = " << (d1 != c1) << endl;
    cout << "true = " << (c1 > b1) << endl;
    cout << "false = " << (c1 > d1) << endl;
    cout << "true = " << (a1 < c1) << endl;
    cout << "false = " << (a1 < b1) << endl;
    cout << "true = " << (a1 >= b1) << endl;
    cout << "false = " << (a1 >= e1) << endl;
    cout << "true = " << (a1 <= e1) << endl;
    cout << "false = " << (e1 <= b1) << endl;
    
    //Задание 3 
    cout << "true = " << !(e1 <= b1 && a1 != c1) << endl;
    cout << "true = " << !(c1 > d1 || d1 != c1) << endl;
    cout << "true = " << (a1 == b1 && a1 != c1) << endl;
    cout << "true = " << (a1 != c1 && a1 <= e1) << endl;
    cout << "true = " << (a1 == b1 || a1 != c1) << endl;
    cout << "true = " << (c1 > b1 || e1 <= b1) << endl;
}
