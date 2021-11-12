# Rising-stars-five-lines
#for loop
#include<iostream>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)  //using nested for loop
	{
		for (int j = 1; j <= i; j++)
		{
			cout << "*";
	    }
		cout << endl;
	}
	return 0;
}
