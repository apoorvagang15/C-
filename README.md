# C++

maximum till i -> 


#include<bits/stdc++.h>
using namespace std;
int main(){
	int n,a[n];
	cin>>n;
	for(int i=0;i<n;i++){
		cin>>a[i];
	}
	int mx = -1999999;
	for(int i=0;i<n;i++){
		mx = max(mx, a[i]);
		cout<<mx<<" ";
	}
	return 0;
}
