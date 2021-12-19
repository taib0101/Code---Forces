//I seek refused with Allah, from the accursed satan
//In the name of Allah , the Entirely Merciful, the Specially Merciful
//problem link: https://codeforces.com/problemset/problem/160/A

//This problem said to be find minimum number of coins, if we sort descending order then it's possible to find minimum coin
#include<bits/stdc++.h>
using namespace std;

bool cmp(int a,int b)
{
    return a > b;
}

int main()
{
    int n, sum1 = 0;
    vector < int > x;
    cin >> n;
    for(int i = 1; i <= n; ++i)
    {
        int m;
        cin >> m;
        sum1 += m;
        x.push_back(m);
    }
    int sum2 = 0,c = 0;
    sort(x.begin(),x.end(),cmp);
    for(int i = 0; i < n; ++i)
    {
        sum2 += x[i];
        sum1 -= x[i];
        c++;
        if(sum2 > sum1)
            break;
    }
    cout << c << endl;
    return 0;
}
