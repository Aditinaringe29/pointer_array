# pointer_array
fetching the location of each element in an array using pointers and for loop.
#include<iostream>
using namespace std;
int main()
{
    int ar1[5]={9,2,5,4,3};
    float ar2[5]={9.1,2.3,5.2,4.8,3.7};
    int i;
    int j;
    int *aptr=&ar1[0];
    float *aptr2=&ar2[0];
    for(i=0;i<5;i++)
    {
        cout<<"the value is "<<*aptr;
        cout<<" and the adress is "<<aptr<<endl;
        aptr=aptr+1;

    }
    for(j=0;j<5;j++)
    {
        cout<<"the value is "<<*aptr2;
        cout<<" and the adress is "<<aptr2<<endl;
        aptr2=aptr2+1;
    }



}
