Aim -> To study and implement C++ Bitwise Operators.

Software -> Visual Studio Code

Theory -> Bitwise Operaotors in C++ are used to perform bit-level operations on the operands.
Its symbols and functions are as follows:
1. & -> Binary AND
2. | -> Binary OR
3. ^ -> Binary XOR
4. << -> Left Shift
5. >> -> Right Shift
6. ~ -> Compelement

Code:
```

#include<iostream> 
using namespace std; 
int main()  
{ 
int a, b, x, y;
cout<<"Enter a number: ";                       
cin>>a; 
cout<<"Enter another number: ";                 
cin>>b; 
cout<<"Binary AND: "<<(a&b)<<"\n";              
cout<<"Binary OR: "<<(a|b)<<"\n";                
cout<<"Binary XOR: "<<(a^b)<<"\n";               
cout<<"Left Shift: "<<(a<<b)<<"\n";              
cout<<"Right Shift: "<<(a>>b)<<"\n";             
cout<<"Complement of a: "<<(x=~a)<<"\n";        
cout<<"Complement of b is: "<<(y=~b)<<"\n";      
return 0;
}
```
Output:
![image](https://github.com/user-attachments/assets/7a2c9681-286a-4113-8214-e7aabdf3a519)

Conclusion -> I learnt about bitwise operators.
