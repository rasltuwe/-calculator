#include <iostream>

using namespace std;

float a, b, c;
char d;
int p;
int main()
{
    setlocale(LC_ALL, "Russian");

    while (p != 2)
    {
        cout << "1 - калькулятор"<<endl;
        cout << "2 - выход"<<endl;
        cin >> p;
        switch (p)
        {
        case 1:
        {
           cout <<"первое число ";
            cin >> a;
            cout << "какое действие вы хотите выполнить ";
            cin >> d;
            cout << "второе число ";
            cin >> b;
            if (d == '+')
                c = a + b;
            if (d == '-')
                c = a - b;
            if (d == '*')
                c = a * b;
            if (d == '/')
                c = a / b;
        }
        case 2:
        {
            break;
        }
        }
        cout << "результат = "  << c <<endl;
    }
}
