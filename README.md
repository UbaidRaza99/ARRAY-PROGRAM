# ARRAY-PROGRAM
(Array Skip 3or5 index) )0r (Reversed)


//Write a program to add 10 integer array elements. Skip value at index 3 and 5
#include <iostream>
using namespace std;
int main(){

int sum=0;
int arr[10];

cout<<"Enter 10 Numbers For sum except index 3 & 5=" ;
for(int i=0;i<=9;i++){
cin>>arr[i];
}

for(int i=0;i<=9;i++){
if(i==3){
	continue;
}
else if(i==5){
	continue;
}

sum=sum+arr[i];
}
cout<<"Sum of 10 Numbers except Index 3 & 5="<<sum;

	return 0;
}



//This a program in which we reversed the array .

#include <iostream>
using namespace std;
int main(){
int arr[10];
for(int i=0;i<=9;i++){
cin>>arr[i];
}

cout<<"Entered Numbers are:"<<endl;
for(int i=0;i<=9;i++){
	cout<<arr[i]<<"  ";
}

cout<<endl;
cout<<"Reversed Numbers are:"<<endl;
for(int i=9;i>=0;i--){

	cout<<arr[i]<<"  ";
}



return 0;
}
