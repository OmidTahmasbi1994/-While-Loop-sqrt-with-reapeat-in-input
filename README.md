# -While-Loop-with-reapeat-in-input

#include <iostream>
#include<cmath>
#include <conio.h>

using namespace std;
int main()

{
	double a;
	
	cout<<"Enter A Positive Number:"<<endl;
	cin>>a;
	
	while (0 < a)
	
	{
		cout<<"sqrt ("<<a<<") = "<<sqrt(a)<<endl;
		
		cout<<"Enter Another Positive Number Or (0 To Quit)"<<endl;
			
		cin>>a;
	}
	
	getch();

}
