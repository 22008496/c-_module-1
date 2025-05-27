
# EX.NO : 1(C)  C++ CONSTRUCTORS AND DESTRUCTORS 

# PROGRAM STATEMENT :

Write a C++ program to display "C++ constructors" using default constructors. 
# ALGORITHM:  

1. Start the program.  
2. Define a class Cont with a default constructor that prints "C++ constructors".  
3. In the main function, create an object c of class Cont, which calls the default constructor and  
displays the message.  
4. End the program. 
 
# PROGRAM :  
#include <iostream> 
using namespace std; 
class Example { 
public: 
Example() { 
cout << "C++ constructors" << endl; 
} 
}; 
int main() { 
Example obj; 
return 0; 
} 
#output:

![alt text](<Screenshot 2025-05-27 085502.png>)

# Result: 
Thus, the C++ program to display "C++ constructors" using a default constructor is created 
successfully. 