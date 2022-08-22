# 100daysofcode
#this is my first program in c++ to print prime no between any range without using function
#include<iostream>
using namespace std;

int main(){
    int a,b;
    cin>>a>>b;
    int i;
    for(i=a;i<=b;i++){
        int j;
        for(j=2;j<i;j++){
            if(i%j==0){
                break;
            }
            
        }
        if(j==i){
        cout<<i<<endl;
        }   
    }
    return 0;
}
