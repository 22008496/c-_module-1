
# EX.NO-1-B-CLASS-SCOPE-AND-ACCESSING-CLASS-MEMBERS-REFERENCE-VARIABLES 

# PROGRAM STATEMENT :  
To write a program in C++ to calculate the volume of a cube(declare side as private member ) using class methods. 

# ALGORITHM :  
1. Start the program.  
2. Define a Cube class with private side variable and public methods to set the side length and  calculate the volume.  
3. In main, read the side length, create a Cube object, set the side, calculate the volume, and print it.  
4. End the program.  

# PROGRAM : 
#include <iostream> 
using namespace std; 
class Cube { 
private: 
float side; 
public: 
Cube(float s) : side(s) {} 
float calculateVolume() { 
return side * side * side; 
} 
}; 
int main() { 
float side; 
cin >> side; 
Cube cube(side); 
cout << "The Volume of Cube is:" << cube.calculateVolume() << endl; 
return 0; 
} 

# output: 

![alt text](<Screenshot 2025-05-26 112132.png>)

# RESULT : 

Thus, the C++ Program to calculate the volume of a cube(declare side as private member ) using 
class methods created successfully.  