#include <iostream>
#include <fstream>


using namespace std;

float*init(void);
float*init(int n);
float*init(int n, float val);

int main(void)
{
	
float* x;
float val;
int n;

n = 1;
x = init();

cout << "\nx = \n";

for(int i=0; i< n; i++) {
	
cout << x[i] << endl;

}

delete [] x;

n = 4;
x = init(n);
cout << "\nx = \n";


for(int i=0; i< n; i++) {
	
cout << x[i] << endl;

}

delete [] x;

n = 5;
val = 1.27;
x = init(n, val);

cout << "\nx = \n";

for(int i=0; i< n; i++) {
	
cout << x[i] << endl;

}


delete [] x;

return 0;

}


float * init(void)
{
	float*x= new float[1];

	x[0]=0.0;
	return x;
}

float * init(int n)
{
	float *x= new float[n];
	for(int i=0; i<n; i++){
		
		x[i]=0.0;
		
	}
	return x;
}

float*init(int n, float val)
{
	float *x=new float[n];
	for(int i=0; i<n; i++){
		x[i]=val;
	
	}
		return x;
}
