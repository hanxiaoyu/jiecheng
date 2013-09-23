jiecheng
========
#include<iostream>
using namespace std;
int S(int m,int n)
{
	int p,s=1;
	p=m-n;
if(n>m)
	cout<<"Error"<<endl;

else{
	for(;m>p;m--)
		s=s*m;
    }
return s;
}
int main()
{
	int m,n;
	cout<<"Input the number m n:"<<endl;
 cin>>m>>n;
 cout<<"结果为:"<<S(m,n)<<endl; 
  system("pause");
   return 0;
}
