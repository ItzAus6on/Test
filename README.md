# hello world

Hi I'm Aus6on,this is my Apps.

IT is my first code：

#include<bits/stdc++.h>
using namespace std;
int a[10][10];
int main(){
	int i,j,n,t=1;
	cin>>n;
	for(i=1;i<=n;i++)
	{
		for(j=1;j<=n;j++)
		{
			a[i][j]=t;
			t++;
		}
	}
	for(i=1;i<=n;i++)
	{
		for(j=1;j<=n;j++)
		{
			cout<<setw(3)<<a[i][j];
		}
		cout<<endl;
	}
   return 0;
}
all right
