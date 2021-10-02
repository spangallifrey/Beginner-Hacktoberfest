
//cgpa calculator
#include<bits/stdc++.h>
using namespace std;
int main()
{
	int n,c,input,prev;
    int total = 0;
	vector<int> cred;
	vector<float> cg;
	vector<int> tot;
	cout<<"Enter Number of Semesters"<<endl;
	cin>>n;


	for(int i=0;i<n;i++)
	{ float l;
      int temp;
      cout<<"Enter No of Credits for Semester "<<i+1<<endl;
      cin>>temp;
      total += temp;
      cred.push_back(temp);
      tot.push_back(total);
       cout<<"Enter cgpa upto Semester "<<i+1<<endl;
      cin>>l;
      cg.push_back(l);
	}
   cout<<"The semester for which you want your sgpa is - ";
   cin>>input;
   cout<<endl;
   float sum = (cg[input-1]*tot[input-1])-(cg[input-2]*tot[input-2]);
   float ans = sum/cred[input-1];
   cout<<ans;
   int j=0;
   
}
