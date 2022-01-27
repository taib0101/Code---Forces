#include<bits/stdc++.h>
using namespace std;

int gcdd(int x, int y)
{
    if(x < y)
        swap(x,y);
    if(x % y == 0)
        return y;
    return gcdd(y,x%y);
}

int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        int n;
        cin >> n;
        int sum = 0;
        vector < int > od, ev, ar;
        for(int i = 0; i < n; ++i)
        {
            int x;
            cin >> x;
            if(x % 2 == 1)
                od.push_back(x);
            else
                ev.push_back(x);
        }
        for(int i = 0; i < ev.size(); ++i)
            ar.push_back(ev[i]);
        for(int i = 0; i < od.size(); ++i)
            ar.push_back(od[i]);
        for(int i = 0; i < n; ++i)
        {
            for(int j = i+1; j < n; ++j)
            {
                if(gcdd(ar[i],2*ar[j]) > 1)
                    sum++;
            }
        }
        cout << sum << endl;
    }
    return 0;
}
