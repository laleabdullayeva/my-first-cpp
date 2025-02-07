# my-first-cpp
#include <iostream>
using namespace std;
class circle {
	public:
		double radius;
		double sahe (){
			return 3.14159*radius*radius;
		}
		
};
int main(){
	circle daire;
	daire.radius=5;
	cout<<"dairenin sahesi:"<<daire.sahe()<<endl;
	return 0;
}
