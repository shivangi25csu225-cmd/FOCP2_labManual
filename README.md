# FOCP-Lab-Manual

#include<iostream>
using namespace std;
class addition
    {   int a,b;
        int sum;//data,pvt
        public:    //functions,public
        void getData();//functions
        void display();//functions

    };
    void addition::getData()//:: scope resolution operator
    {
        cout<<"Enter first number";
        cin>>a;
        cout<<"Enter second number";
        cin>>b;
    };
void addition::display()
{
    sum =a+b;
    cout<<"sum of two numbers is"<<sum;
};
int main(){
    addition a1 ;
    a1.getData();
    a1.display();
    return 0;
}
