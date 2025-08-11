#include<iostream>
using namespace std;
void change (int data);
int main()
{
	int data= 2;
	change(data);
	cout<<"value of the data is "<<data<<endl;
	return 0;
}
void change(int data)
{
	data=5;
}
