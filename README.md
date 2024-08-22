#   AIM

To learn about VS code and getting input from user and displaying it.

# Software Used
VS Code and Cpp online Compiler

# Problem Statement
 1.) Write a program to print simple 'Hello world' message.

 2.) Write a program to get the  input from user and displaying it.
 
 3.) Write a program to create a basic calculator.

 # Theory
To print a message or output we use _'cout'_ .

The namespace is used to decrease or limit the scope of any variable or function.
 
 _'endl'_ is used to move the cursor to the new line.
# Program 
## User Input
#include<iostream>
using namespace std;
int main()
{
    string a;
    cout << "Enter your name ";
    getline(cin,a);
    cout<<"Hello  " <<a;
    return 0;
}
## Hello World
include<iostream>
using namespace std;
int main()
{
    cout<< "Hello World!";
    return 0;
}
## Calculator
#include<iostream>
using namespace std;
int main()
{ float a,b,c,d,e,f;
    cout<<"enter first number ";
    cin >> a;
    cout<< "enter second number ";
    cin >> b;
    c = a+b ;
    cout << "Sum is: " <<c<<endl;
    d = a-b;
    cout<< "Difference is: "<<d<<endl;
    e = a*b;
    cout<<"Product is:" << e <<endl;
    f = a/b;
    cout<<"Quotient is: "<<f<<endl;
    return 0;
}
# Output
### User Input
![User Input](https://github.com/user-attachments/assets/cfab0e45-7ed0-45f3-aeeb-b11582cc8b81)
### Hello World
![hello](https://github.com/user-attachments/assets/e1370f61-081f-49d9-976c-64d3302e06eb)
### Calculator
![Exp 1 calci](https://github.com/user-attachments/assets/88369368-3d7f-4b3b-862c-31670fb22b8e)
# Conclusion
We learnt how to take input from user and print it, we learnt to use basic operators like +, - , * and /.


