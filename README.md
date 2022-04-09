#include <iostream>
using namespace std;

int main()
{
    int i,j,k,n;
    cout <<"Enter the number = ";
    cin>>n;
    for(i=1;i<=n;i++) //rows
    {
        for(j=1;j<i;j++) //space
        {
            cout<<" ";
        }
        for(k=i;k<=n;k++)
        {
           cout<< i ;
        }
        cout<<"\n";
    }
    return 0;
}
