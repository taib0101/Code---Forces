
//I seek refused with Allah, from the accursed devil
//In the name of Allah, the Entirely Merciful, the Specially Merciful
#include<bits/stdc++.h>
using namespace std;
string anss(string x)
{
    string y;
    int s = x.size();
    int d1, d2;
    int a = 0, b = 0;
    for(int i = s-1; i > 0; --i)
    {
        d1 = x[i] - '0';
        d2 = x[i-1] - '0';
        //cout << "d1 = " << d1 << " , d2 = " << d2 << endl;
        if((d1 + d2) > 9)
        {
            a = i - 1;
            b = i;
            break;
        }
    }
    if(!a && !b)
    {
        d1 = x[0] - '0';
        d2 = x[1] - '0';
        a = 0;
        b = 1;
    }
    int c = d1 + d2;
    string z;
    while(c)
    {
        z.push_back((c % 10) + '0');
        c /= 10;
    }
    reverse(z.begin(),z.end());
    for(int i = 0; i < a; ++i)
        y.push_back(x[i]);
    y += z;
 
    for(int i = b+1; i < s; ++i)
        y.push_back(x[i]);
    //cout << d1 + d2 << endl;
    return y;
}
int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        string x, y;
        cin >> x;
        cout << anss(x) << endl;
    }
    return 0;
}
