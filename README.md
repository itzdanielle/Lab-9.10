# Lab-9.10
#include <iostream>
using namespace std;

int main() {
  int num1, num2;

  cout << "Please enter an integer\n";
  cin >> num1;
  cout << "Enter another integer\n";
  cin >> num2;

  if (num1 > num2) // if the first number entered is bigger it will have this output
    cout << num1 << " is bigger.\n";
  else if (num1 < num2) // if the second number entered is bigger than 1st number it will be this output 
    cout << num2 << " is bigger.\n";
  else
    cout << "The numbers are the same.\n"; // this is here to catch any errors

}
