# joshuamacaballug-assesment-1
#include <iostream>
using namespace std;

int main()
{
    cout << "Please State your age:\n";
    int x;
    cin >> x;
    if (x == 16 || x == 17 || x == 18 || x == 19 || x == 20 || x == 21)
    {
        cout << "Your age is eligible to enter the malls.\n";
        cout << "Would you like to go to the mall?\n";
        char input;
        cin >> input;
        switch (input) {
        case 'Y':
            cout << "Alright, enjoy your day!";
            break;
        case 'N':
            cout << "Alright, thank you.";
            break;
        }
    }
    if (x == 22 || x == 23 || x == 24 || x == 25 || x == 26 || x == 27 || x == 28 || x == 29 || x == 30)
    {
        cout << "Your age is eligible to travel Hawaii.\n";
        cout << "Would you like me to book you a flight to Hawaii?\n";
        char input;
        cin >> input;
        switch (input) {
        case 'Y':
            cout << "Alright, enjoy your vacation!";
            break;
        case 'N':
            cout << "Alright, thank you.";
            break;
        }
    }
}
