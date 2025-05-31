# PROTECTED MEMBERS & OVERRIDING

## PROGRAM STATEMENT :

To write a c++ program to implement protected member with integer values.

## ALGORITHM:  

1.	Start the program.
2.	Define a class A with protected attributes regno, name, and gender, and a public method get to read values for these attributes.
3.	Define a derived class B that inherits from class A and includes a display method to output the employee details.
4.	In the main function, create an object obj of class B, call get to read input, and then call display to print the employee details.
5.	End the program.

## PROGRAM:
```
#include<iostream> using namespace std; class A{
protected:
int a; public:
void read(){ cin>>a;
cout<<"Thevalueof num is: "<<a;
}
};
int main(){ A a; a.read();
}
 ```
## OUTPUT :
![image](https://github.com/user-attachments/assets/f15e8e02-fe49-4768-b5de-a3a774e444b9)

## RESULT :

Thus, the C++ program to implement protected member with integer values is created successfully.



