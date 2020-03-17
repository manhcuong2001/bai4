#include<iostream>
#include<stdio.h>
#include<vector>
#include<string.h>
using namespace std;
int main()
{
	vector<float>A;
	double x, tong=0,dem=0;
	do
	{
		cout<<"Nhap vao mot so:";cin>>x;
		A.push_back(x);
	} 
		while (x>=0);
		A.pop_back();
		for(int i=0;i<A.size();i++)
		{
		 	cout<<A[i]<<" ";
		 	tong+=A[i];
		 	dem+=i;
		}
		cout<<"So phan tu cua vecto:"<<dem;
		cout<<"\nTong cac phan tu ="<<tong;
	return 0;
}
    
