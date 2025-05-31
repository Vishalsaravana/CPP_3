# PUBLIC,PRIVATE & PROTECTED INHERITANCE

## PROGRAM STATEMENT :

To write a c++ program to find sum & product of two numbers using Hierarchical inheritance.
## ALGORITHM:  

1.	Start the program.
2.	Define a class Snake with integer attributes a, b, c, and d, and a method get to read values for these attributes.
3.	Define a class Cobra that inherits from Snake and includes a method pro to calculate and display the product of a and b.
4.	Define a class King that inherits from Cobra and includes a method summ to calculate and display the sum of c and d.
5.	In the main function, create an object obj of class King, call get to read input values, call pro to display the product of a and b, and call summ to display the sum of c and d.
6.	End the program.

## PROGRAM:
```
#include<iostream> using namespace std; class Snake{
public:
int a,b,c,d; voidget(){
cin>>a>>b>>c>>d;
}
};
class Cobra: public Snake{ public :
void pro(){ cout<<"Product="<<a*b<<endl;  }
};
class King: public Cobra{ public:
void summ(){ cout<<"Sum="<<c+d;
}
};
int main(){
 
King obj; obj.get();
obj.pro();
obj.summ();

}
```

## OUTPUT :
![image](https://github.com/user-attachments/assets/d395acf0-cebd-48bb-8e1a-0526b1b555ea)

## RESULT :

Thus, the C++ program to find sum & product of two numbers using Hierarchical inheritance is created successfully.


