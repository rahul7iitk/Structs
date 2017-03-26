#include <bits/stdc++.h>
using namespace std;

struct A
{
    int start;int end;
};

int main() {
	
	int n;
	cin>>n;
	
	A m[n];
	int a[n],b[n];
	
	for(int i=0;i<n;i++)
	{
	    cin>>a[i];
	    cin>>b[i];
	    m[i].start=a[i];
	    m[i].end=b[i];
	    
	}
	
	for(int i=0;i<n;i++)
	cout<<m[i].start<<" "<<m[i].end<<endl;
	
	return 0;
}
