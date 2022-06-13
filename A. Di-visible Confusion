#include<bits/stdc++.h>
using namespace std;
#define ll long long

bool cheack(ll ar[],int n)
{
    for(int i = n; i >= 1; --i)
    {
        ll j =(ll) i;
        while(j >= 1 && ar[i] % (j+1) == 0)
        {
            if(j == 1)
                return 0;
            //cout << "h = " << ar[i] << endl;
            j--;
        }
    }
    return 1;
}

int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        int n;
        cin >> n;
        ll ar[n+10];
        for(int i = 1; i <= n; ++i)
            cin >> ar[i];
        if(cheack(ar,n))
            cout << "Yes" << endl;
        else
            cout << "No" << endl;
    }
    return 0;
}
