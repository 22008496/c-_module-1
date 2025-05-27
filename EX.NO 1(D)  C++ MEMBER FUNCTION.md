
# EX.NO : 1(D)  C++ MEMBER FUNCTION  

# PROGRAM STATEMENT :  

To write a C++ program to convert Celsius into Fahrenheit using inline function 

# ALGORITHM : 

1. Start the program.  
2. Define an inline function convertToFahrenheit that takes a float celsius as input and returns the Fahrenheit equivalent using the formula (celsius * 9.0 / 5.0) + 32.  
3. In the main function, declare a float variable celsius to store the temperature.  
4. Read the Celsius temperature from the user and store it in celsius.  
5. Call the convertToFahrenheit function with celsius as the argument and store the result in the fahrenheit variable.  
6. Print the converted temperature in Fahrenheit.  
7. End the program. 

# Program: 
```
#include <iostream>
using namespace std;
inline float convertToFahrenheit(float celsius) {
    return (celsius * 9.0 / 5) + 32;
}

int main() {
    float celsius;
    cin >> celsius;
    cout << "temperature in Fahrenheit:" << convertToFahrenheit(celsius) << endl;
    return 0;
}

```
# output: 

![Screenshot 2025-05-27 085936](https://github.com/user-attachments/assets/93e96b4c-e7e8-4055-bd06-64362fed71dc)

# Result: 
Thus, the C++ program to convert Celsius into Fahrenheit using inline function is implemented successfully. 
