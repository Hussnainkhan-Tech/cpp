
#include<iostream>
using namespace std;
//Function are used only for calling the function when some want to execute statement they call one time like this
void show(){
	cout<<"Hello world";
}
int main(){
	show();
	return 0;
}


//some want to to execute this function more than one
void show(){
	cout<<"Hello world"<<endl;
}
int main(){
	show();
	show();
	show();
	return 0;
	}


//if you want to add two numbers in function 
#include<iostream>
using namespace std;
int sum(int a, int b){
	return a+b;
}
int main(){
	int a,b;
	cout<<"Enter the number "<<endl;
	cin>>a>>b;
	cout<<sum(a,b);
	return 0;
	}



//if you want to Substract  two numbers in function 
#include<iostream>
using namespace std;
int substract(int a, int b){
	return a-b;
}
int main(){
	int a,b;
	cout<<"Enter the number "<<endl;
	cin>>a>>b;
	cout<<substract(a,b);
	return 0;
	}

//if you want to get average of  two numbers in function 
#include<iostream>
using namespace std;
float avg(float a, float b){
	return (a+b)/2.0;
}
int main(){
	float a,b;
	cout<<"Enter the number "<<endl;
	cin>>a>>b;
	cout<<avg(a,b);
	return 0;
	}
