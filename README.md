#include <iostream>
#include <cmath>

using namespace std;

int main()
{
    double x;   // вхідний аргумент
    double y;   // результат обчислення виразу

    cout << "x = "; cin >> x;

    // розгалуження в повній формі
    if (x <= -4)
        y = -2;
    else
        if (-4 < x && x <= 0)
            y = x / 4;
        else
            if (0 < x && x <= 2)
                y = x * x;
            else
                y = -x / 2 + 5;

    cout << endl;
    cout << "y = " << y << endl;

    cin.get();
    return 0;
}
