#include<bits/stdc++.h>
using namespace std;
#define ll long long
int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        int n;
        cin >> n;
        int x = sqrt(n), y = 1;
        int to = x;
        y = y * pow(n,0.34);
        for(ll i = 1; i <= x; ++i)
        {
            ll a = i * i * i;
            ll b = sqrt(a);
            if(a != (b * b) && a <= n)
            {
                // cout << "a = " << a << endl;
                // cout << "b = " << b * b << endl;
                to++;
            }
                
        }
        cout << to << endl;
        //cout << "x = " << x << " , y = " << y << endl;
    }
    return 0;
}
