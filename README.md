# first-one

#include<iostream>
using namespace std;
#include<conio.h>
int fact(int);
main()
{
	int p;
	cout<<"enter an no to find its factorial";
	cin>>p;
	cout<<"factorial of the no is "<<fact(p);
	
	getch();
	
}


int fact(int z)
{
	if(z==1)
	return 1;
	  else 
	   return(z*fact(z-1));
	
	
	
}
