//I seek refused with Allah,from the accursed satan
//In the name of Allah, the Entirely Merciful,the Specially Merciful
//problem link: https://codeforces.com/problemset/problem/337/A
#include<bits/stdc++.h>
using namespace std;

int main()
{
    int n, m;
    cin >> n >> m;
    int arr[m+10];

    for(int i = 0 ;i < m; ++i)
    {
        int x;
        cin >> x;
        arr[i] = x;
    }
    sort(arr,arr+m);
    int minn, maxx, minn2 = 1000000;
    for(int i = 0; i < m; ++i)
    {
        if(m-i+1 >= n)
            minn = 1000000, maxx = 0;
        for(int j = i,jj = 1; jj <= n && m-i+1 >= n; ++j,++jj)
        {
            
            minn = min(minn,arr[j]);
            maxx = max(maxx,arr[j]);
        }
        minn2 = min(minn2,(maxx-minn));
    }
    
    cout << minn2 << endl;
    return 0;
}
