#include <iostream>
#include <cmath>
using namespace std;
//Calculator
int main()
{
    double num1,num2;
    char A;
    cout<<"Enter first number :";
    cin>>num1;
    cout<<endl;
    //Symbols of math
    cout<<"Enter one of these Symbols (+ - * /) :";
    cout<<endl;
    cin>>A;
    cout<<"Enter second number :";
    cin>>num2;
    cout<<endl;
    switch(A) {

    case '+': cout<<num1<<" + "<<num2<<" = "<<num1+num2;
    break;
    case '-': cout<<num1<<" - "<<num2<<" = "<<num1-num2;
    break;
    case '*': cout<<num1<<" * "<<num2<<" = "<<num1*num2;
    break;
    case '/': cout<<num1<<" / "<<num2<<" = "<<num1/num2;
    break;

    default: cout<<"Error";


    }



    return 0;
}
