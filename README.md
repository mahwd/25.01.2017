
include <iostream>
#include <string>
using namespace std;

int main()
{
   int a,b,c,m,n,k;
    
    cin >> a >> b >> c;
    
  m=a%2;
  n=b%2;
  k=c%2;
  
    
    if ((((m||n||k)==1) && ( (m&&n&&k)==0))) {
    
    cout << "yes";
        } else cout<<"no";
    
  return 0; 
}"
