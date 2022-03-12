#include<bits/stdc++.h>
using namespace std;
#define ll long long
int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        ll w, h;
        cin >> w >> h;
        ll maxx = 0;
        for(int i = 1; i <= 4; ++i)
        {
            ll q, p;
            cin >> q >> p;
            for(int j = 2; j <= q; ++j)
            {
                ll x;
                cin >> x;
                if(i <= 2)
                    maxx = max(maxx,(abs(x-p) * h));
                else
                    maxx = max(maxx,(abs(x-p) * w));
                    
            }
        }
        cout << maxx << endl;
    }
    return 0;
}
