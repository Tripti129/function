ques: Divisiblity Problem
// Online C++ compiler to run C++ program online
#include <iostream>
using namespace std;
int main() {
   int n;
   cin>>n;
   while(n--){
       int a,b;
       cin>>a>>b;
   int count=0;
    
   while(a%b!=0){
       a=a+1;
       count++;
   }
   cout<<count;
   }
    return 0;
}
