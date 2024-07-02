# lecture-13---cipher-school
In this lecture i had leaned about the functions part 1 that how function will work what the functions can do where can the functions will work where to place how to call them and how to create them 
hewre is the simple defination about the functions here we go Functions are blocks of code that perform specific tasks and can be called (invoked) from other parts of a program. They help in organizing code, making it reusable, and improving readability.  Here is the simple example of using function we can add to numbers using function here is the code 
#include <iostream>
using namespace std;
int add(int a, int b);

int main() {
    int num1, num2, sum;

    
    cout << "Enter first number: ";
    cin >> num1;
    cout << "Enter second number: ";
    cin >> num2;

   
    sum = add(num1, num2);

  
    cout << "The sum is: " << sum << endl;

    return 0;
}

int add(int a, int b) {
    return a + b;
}

