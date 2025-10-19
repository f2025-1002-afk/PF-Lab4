#include <iostream>
using namespace std;

int main() {
    int percentage;
    char grade;

    cout << "Enter student's percentage (0 - 100): ";
    cin >> percentage;

    if (percentage < 0 || percentage > 100) {
        cout << "Invalid percentage entered!" << endl;
       break;
    }
    switch (percentage / 10) {
        case 10: // for 100
        case 9:
            grade = 'A';
            break;
        case 8:
            grade = 'B';
            break;
        case 7:
            grade = 'C';
            break;
        case 6:
            grade = 'D';
            break;
        default:
            grade = 'F';
    }

    cout << "Grade: " << grade << endl;

    return 0;
}
