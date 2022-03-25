//I seek refused with Allah,from the accursed satan
//In the name of Allah, the entirely mercifull,the specially mercifull
//link :- https://codeforces.com/problemset/problem/1607/B

#include<bits/stdc++.h>
using namespace std;
#define ll long long

int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        ll x, n, a;
        cin >> x >> n;
        a = x;
        for(ll i = 1; i <= 2 && i <= n; ++i)
        {
            if(x % 2)
                x += i;
            else
                x -= i;
            a = x;
        }
        if(n <= 2)
            cout << a << endl;
        else
        {
            ll b = (n % 4 == 2) ? -1 : ((n / 4) * 4) - 2;
            if(n == 3)
                b = 2;
            if(b == -1)
                cout << a << endl;
            else
            {
                //x = a;
                for(ll i = b+1; i <= n; ++i)
                {
                    if(x % 2)
                        x += i;
                    else
                        x -= i;
                    a = x;
                }
                cout << a << endl;
            }
        }
    }
    return 0;
}
