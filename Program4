#include <iostream>
using namespace std;
int main() {
    int units;
    int type;  
    float bill = 0;

    cout << "Enter number of units consumed: ";
    cin >> units;

    cout << "Select connection type:\n";
    cout << "1. Domestic\n";
    cout << "2. Commercial\n";
    cout << "Enter your choice (1 or 2): ";
    cin >> type;

    switch (type) {
        case 1: // Domestic
            if (units <= 100) {
                bill = units * 10;
            } else {
                bill = 100 * 10 + (units - 100) * 15;
            }
            cout << "Connection Type: Domestic" << endl;
            break;

        case 2: // Commercial
            if (units <= 100) {
                bill = units * 20;
            } else {
                bill = 100 * 20 + (units - 100) * 25;
            }
            cout << "Connection Type: Commercial" << endl;
            break;

        default:
            cout << "Invalid connection type selected!" << endl;
            break; 
    }

    cout << "Total Bill:Rs "<<bill << endl;

    return 0;
}