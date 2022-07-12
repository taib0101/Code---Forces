#include<bits/stdc++.h>
using namespace std;

int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        int n;
        cin >> n;
        int sum = 0;
        int o = 0,t = 0;
        for(int i = 1; i <= n; ++i)
        {
            int c;
            cin >> c;
            sum += c;
            if(c == 1)
                o++;
            else
                t++;
        }
        if(sum % 2 == 0)
        {
            sum /= 2;
            if((sum %2 == 0) || (sum %2 == 1 && o != 0))
                cout << "Yes" << endl;
            else
                cout << "No" << endl;
        }
        else
            cout << "No" << endl;
    }
    return 0;
}
