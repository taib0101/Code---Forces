#include<bits/stdc++.h>
using namespace std;

bool check(long long int n)
{
    while(!(n % 2))
        n = n / 2;
    //cout << "n = " << n << endl;
    if(n % 2 == 1 && n > 1)
        return 1;
    return 0;
}

int main()
{
    long long int n;
    int t;
    cin >> t;
    while(t--)
    {
        cin >> n;
        if(check(n))
            cout << "YES" << endl;
        else
            cout << "NO" << endl;
    }
    return 0;
}
