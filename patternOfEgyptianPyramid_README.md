# 100daysofcode
this is my commitment to code for straight 100 days with tweet and sharing link on github repo

#include<iostream>
using namespace std;

int main(){

    int n;
    cin>>n;

    for(int i=1;i<=n;i++){
        for(int j=1;j<=i;j++){
           if(j<=n-i){
            cout<<" ";
           }
           
           else{
            cout<<"*";
           }
        }
        cout<<endl;
    }
}
