//size-of-char-int-float-double and product of two numbers entered by the user
//the first program gives the size in bytes of a char,int,float and double.The second program gives the product of two numbers entered by the user.
//the first program's code is below.
#include<iostream>
using namespace std;
main()
{
    int a;
    char key;
    float x;
    double b;
    cout<<"size of char:"<<sizeof(key)<<" byte\n";
    cout<<"size of int:"<<sizeof(a)<<" bytes\n";
    cout<<"size of float:"<<sizeof(x)<<" bytes\n";
    cout<<"size of double:"<<sizeof(b)<<" bytes";
}
//the second program's code is below
#include<iostream>
using namespace std;
int main()
{
    double x,y;
    cout<<"Enter first number upto 2 decimal places:";
    cin>>x;
    cout<<"Enter second number upto 2 decimal places:";
    cin>>y;
    cout<<"Product of these numbers: "<<x*y;
    return 0;
}

