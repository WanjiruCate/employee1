# employee1
#include<iostream>
using namespace std;
class employee
{
private:
string name;
string staffno;
int pay;
string department;
public:
int getpay(int);
employee();
employee(string,string,string);
void display();
};
public employee::employee()
{
name="null";
staffno="null";
pay=0.0;
department="null";
}
public employee::employee(string,string,string)
{
name=na;
staffno=snum;
pay=p;
department=dp;
}
public employee::void display()
{
cout<<"name"<<na;
cout<<"pay"<<p;
cout<<"staffno"<<snum;
cout<<department"<<dp;
}
public::string getpay(int)
{
pay=p;
}
int main()
{
cout<<"Employee Details"<<endl;
cout<<"__________________________________"<<endl;
employee employee1;
employee employee2(string,string,string);
employee1.getpay(int);
employee1.display();
cout<<"Employee1 details"<<endl;
cout<<"name"<<na<<endl;
cout<<"staffnumber"<<snum<<endl;
cout<<"pay"<<p<<endl;
cout<<"department"<<dp<<endl;
cout<<"____________________________________"<<endl;
employee2.getpay(int);
employee2.display;
cout<<"Employee1 details"<<endl;
cout<<"name"<<na<<endl;
cout<<"staffnumber"<<snum<<endl;
cout<<"pay"<<p<<endl;
cout<<"department"<<dp<<endl;
cout<<"____________________________________"<<endl;
cout<<endl;
return 0;
}

