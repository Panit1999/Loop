#include<iostream>
#include<time.h>
using namespace std;
int main(){
    int a=0,i=1;
     cout << "------------------------------------------------------"<< endl;
    int round = rand()%20+1;
    a = 0;
    for (i = 1; i < 5; i++)
    {
        cout<<"Enter lucky number "<<i<<" (1-20) : ";
        cin>>a;
        if(a == round){
            cout<<"Lucky!!!!\n";
            cout<<"You got 1,000,000 bath\n";
            break;
        }else cout<<"This is wrong number\n";
    }
  return 0;  
}
