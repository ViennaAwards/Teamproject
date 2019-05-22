#include<iostream>
using namespace std;
int main(){
	char c;
	int a,b;
	double res;
	cout<<"어떠한 연산을 하시겠습니까?";
	cin>>c;
	cout<<"a와 b의 값 입력:";
	cin>>a>>b;
	switch(c){
		case '+':res=a+b;
					cout<<res<<endl;
			break;
		case '-':res=a-b;
					cout<<res<<endl;
			break;
		case '*':res=a*b;
					cout<<res<<endl;
			break;
		case '/':res=a/b;
					cout<<res<<endl;
			break;
			default:cout<<"error"<<endl;
	}
}
