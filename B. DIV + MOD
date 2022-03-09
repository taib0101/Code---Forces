#include<bits/stdc++.h>
using namespace std;

int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        int l, r, a, x = 0;
        cin >> l >> r >> a;
        if(r >= a)
        {
            if((r + 1) % a == 0 && r != 1)
                x = (r / a) + (r % a);
            else
            {
                int rr = (r / a) * a;
                if(l != r)
                    rr--;
                if(l <= rr && rr <= r)
                    x = (rr / a) + (rr % a);
                else
                    x = (r / a) + (r % a);
                //cout << "r = " << rr << endl;
            }
        }
        else if(r < a)
            x = (r / a) + (r % a);
        cout << x << endl;
    }
    return 0;
}
