# rerere
#include <iostream>
#define _USE_MATH_DEFINES
#include <math.h>
#include "windows.h"
#include <cmath>
#include <iomanip>


using namespace std;

int main()
{
    //Завдання 1
    SetConsoleCP(1251);
    SetConsoleOutputCP(1251);

    double x, y, z;
    int sc, tm;

    cout << "Введіть ваш час години, хвилини та секунди:";
    cin >> x >> y >> z;
    sc = (x * 3600) + (y * 60) + z;
    tm = sc / 60;
    cout << "Всього пройшло\t" << sc << "\tсекунд" << endl;
    cout << "Всього пройшло\t" << tm << "\tхвилин" << endl;

}

