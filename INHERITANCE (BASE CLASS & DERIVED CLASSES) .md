# INHERITANCE(BASE CLASS & DERIVED CLASSES)

## PROGRAM STATEMENT :

To write a c++ program to read empno,empname & empgender in one class and display the above details in another class using inheritance.
## ALGORITHM:  

1.	Start the program.
2.	Define a class A with protected attributes regno, name, and gender, and a public method get to read values for these attributes.
3.	Define a derived class B that inherits from class A and includes a display method to output the employee details.
4.	In the main function, create an object obj of class B, call get to read input, and then call display to print the employee details.
5.	End the program.

## PROGRAM:

```
#include <iostream> using namespace std; class A
{
protected: int regno;
string name,gender; public:
void get(){ cin>>regno>>name>>gender;
}
};
class B:public A{ public:
voiddisplay(){
cout<<"Employee Number: "<<regno<<endl; cout<<"Employee Name: "<<name<<endl; cout<<"Employee Gender: "<<gender;
}
};
int main(){
 
B obj; obj.get(); obj.display();
}
```

## OUTPUT :
![image](https://github.com/user-attachments/assets/56ea66e5-0fa0-4289-9e67-a4cc16b4dfc0)

## RESULT :

Thus, the C++ program to read empno,empname & empgender in one class and display the above details in another class using inheritance is created successfully.


