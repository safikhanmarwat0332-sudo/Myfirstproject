# Myfirstproject#include <iostream>
using namespace std;

int main()
{
    float c, f;

    // Input temperature in Celsius
    cout<<"hello this is a temperature converter"<<endl;
    cout << "Enter temperature in Celsius: ";
    cin >> c;

    // Conversion frmula
    f = c *(9/5 + 32);

    // Display result
    cout << "Temperature in Fahrenheit: " << f << endl;

    return 0;
}
