#include<bits/stdc++.h>
using namespace std;

int ans(int n)
{
    int x = log10(n) + 1;
    int y = 0;
    for(int i = 1; i < x; ++i)
        y += 1 << i;
    int sum = 0;
    for(int i = 0; i < (1 << x); ++i)
    {
        int m = i,cn = 1, t = 0;
        sum = 0;

        while(m)
        {
            int bin = m % 2;
            if(bin)
                sum += cn * 7;
            else
                sum += cn * 4;
            cn = cn * 10;
            m /= 2;
            t++;
        }

        for(int j = t+1; j <= x; ++j)
        {
            sum += cn * 4;
            cn = cn * 10;
        }
        if(n >= sum)
            y++;
        else
            break;
        //cout << "sum = " << sum << endl;
    }
    //cout << "x = " << y << endl;
    return y;
}

int main()
{
    int n;
    cin >> n;
    cout << ans(n) << endl;
    return 0;
}
