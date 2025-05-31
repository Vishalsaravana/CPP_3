# CONSTRUCTOR & DESTRUCTOR IN DERIVED CLASS

## PROGRAM STATEMENT :

To write a C++ program to pass a password (Admin@123 )to the parameterized constructor of a base class through the derived class constructor.

## ALGORITHM:  

1.	Start the program.
2.	Define a class Parent with a public string attribute n initialized to "Admin@123", and a constructor that outputs the password passed to the base class.
3.	Define a class Child that inherits from Parent and has a constructor that outputs the password received from the base class.
4.	In the main function, create an object c of class Child, which automatically calls the constructors of both Parent and Child to display the messages.
5.	End the program.

## PROGRAM:
```
#include<iostream> using namespace std;

class Parent { public:
string n="Admin@123"; Parent(){
cout<<"The Passwordpassed to thebaseclass is "<<n<<endl;
}
};

class Child: public Parent
{
public:
Child(){
cout<<"The Password"<<n<<" is passedthroughthederivedclassconstructor";
}
};
int main()
{
Child c;
}
``` 
## OUTPUT :
![image](https://github.com/user-attachments/assets/dd542c22-64d6-4ee5-8352-8622ec2b8a46)

## RESULT :

Thus, the C++ program to pass a password (Admin@123 )to the parameterized constructor of a base class through the derived class constructor is created successfully.


