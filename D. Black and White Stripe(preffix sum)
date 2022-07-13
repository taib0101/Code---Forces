//minimum number of black in segment of k
#include<bits/stdc++.h>
using namespace std;

int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        int n, k;
        cin >> n >> k;
        char c[n+10];
        c[0] = '.';
        int cnt1 = 0,cnt2 = 0;
        int ar[n+10];
        bool bb = 1;
        ar[0] = 0;

        for(int i = 1; i <= n; ++i)
        {
            cin >> c[i];
            if(c[i] == c[i-1] && c[i] == 'B')
            {
                cnt1++;
                if(cnt1 == k)
                    bb = 0;
            }
            else
                cnt1 = 0;
            if(c[i] == 'W')
                cnt2++;
            ar[i] = cnt2;
        }
        int minn = 1e9;
        for(int i = 1; (i+(k-1)) <= n; ++i)
        {
            int j = i+k-1;
            minn = min(minn,ar[j] - ar[i-1]);
        }
        if(!bb)
            minn = 0;
        cout << minn << endl;
    }
    return 0;
}
