// GPA-average-for-grades
#include <iostream>

using namespace std;

int main()
{

    double x;
    cin>>x;
    if (x<=100&&x>=90)
        cout<<"A";
            else if (x<=89&&x>=80)
            cout<<"B";
else if (x<=79&&x>=70)
    cout<<"C";
else if (x<=69&&x>=60)
    cout<<"D";
else if (x<60)
    cout<<"F";
    return 0;
}
