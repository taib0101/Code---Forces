//I seek refused with Allah form the accursed devil
//In the name of Allah , the entirely merciful,the specially merciful
//5 20 15 25
//5 15 20 25
//5 25 20 15

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
        ll ar[n+10];
        ll sum = 0;
        for(int i = 1; i <= n; ++i)
            cin >> ar[i];
        if(n == 1)
            cout << ar[n] << endl;
        else
        {
            for(int i = 1; i <= n; ++i)
            {
                if(ar[i] > ar[i+1] && i == 1)
                    sum += abs(ar[i] - ar[i+1]),ar[i] = ar[i+1];
                else if(i != 1 && i != n)
                {
                    if(ar[i] > ar[i-1] && ar[i] > ar[i+1])
                    {
                        ll x = max(ar[i-1],ar[i+1]);
                        sum += abs(x-ar[i]);
                        ar[i] = x;
                    }
                }
                if(i == n && ar[i] > ar[i-1])
                    sum += abs(ar[i] - ar[i-1]), ar[i] = ar[i-1];
            }
            //cout << "su = " << sum << endl;
            sum += ar[1] + ar[n];
            for(int i = 1; i < n; ++i)
                sum += abs(ar[i] - ar[i+1]);
            cout << sum << endl;
        }
        
    }
    return 0;
}
