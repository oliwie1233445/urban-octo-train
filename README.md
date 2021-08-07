simple c ++ calculator 

# include <iostream>
using namespace std;

int main() {
    
    float numer1, numer2;
    char opcj;
    cout << "podaj dzialanie: +, -, *, /: ";
    cin >> opcj;

    cout << "podaj 2 liczby ";
    cin >> numer1 >> numer2;

    switch (opcj) {
    case '+':cout << numer1 << " + " << numer2 << " = " << numer1 + numer2;
        break;

    case '-': cout << numer1 << " - " << numer2 << " = " << numer1 - numer2;
        break;

    case '*':cout << numer1 << " * " << numer2 << " = " << numer1 * numer2;
        break;

    case '/' :cout << numer1 << " / " << numer2 << " = " << numer1 / numer2;
        break;

    default:
       
        cout << "error!";
        break;
    }

    return 0;
}
