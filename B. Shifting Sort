#include<bits/stdc++.h>
using namespace std;
struct ele
{
    int aa;
    int bb;
    int cc;
};
vector < int > rotatee(vector < int > a,int i,int j)
{
    vector < int > b;
    for(int ii = 0; ii < i; ++ii)
        b.push_back(a[ii]);
    b.push_back(a[j]);
    for(int ii = i; ii < j; ++ii)
        b.push_back(a[ii]);
    int as = a.size();
    for(int ii = j+1; ii < as; ++ii)
        b.push_back(a[ii]);
    return b;
}

int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        int n;
        cin >> n;
        vector < int > a;
        for(int i = 0; i < n; ++i)
        {
            int c;
            cin >> c;
            a.push_back(c);
        }
        vector < ele > vp;
        for(int i = 0; i < n-1; ++i)
        {
            int ii = i;
            for(int j = ii+1; j < n; ++j)
            {
                if(a[i] > a[j])
                {
                    a = rotatee(a,i,j);
                    
                    // for(int k: a)
                    //     cout << k << " ";
                    // cout << endl;
                    vp.push_back({i+1,j+1,j-i});
                    i = ii-1;
                    break;
                }
            }
        }
        cout << vp.size() << endl;
        int vs = vp.size();
        for(int i = 0; i < vs; ++i)
            cout << vp[i].aa << " " << vp[i].bb << " " << vp[i].cc << endl;
    }
    return 0;
}
