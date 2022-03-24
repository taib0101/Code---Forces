//I seek refused with Allah, from the accursed satan
//In the name of Allah, The entirely mercifull, the specially mercifull
//link :- https://codeforces.com/problemset/problem/459/A
//by me sqaure from 4 exis 

#include<bits/stdc++.h>
using namespace std;

int main()
{
    int x1, y1, x2, y2;
    cin >> x1 >> y1 >> x2 >> y2;
    if(abs(x1-x2) == abs(y1-y2) || abs(x1-x2) == 0 || abs(y1-y2) == 0)
    {
        int a = (abs(x1-x2) != 0) ? abs(x1-x2) : abs(y1-y2);
        //cout << "a = " << a << endl;
        if(abs(x1-x2) == abs(y1-y2))
            cout << x1 << " " << y2 << " " << x2 << " " << y1 << endl;
        else
        {
            if(x1 == x2)
                x1 += a, x2 = x1;
            else
                y1 += a, y2 = y1;
            cout << x1 << " " << y1 << " " << x2 << " " << y2 << endl;
        }
    }
    else
        cout << "-1" << endl;
    return 0;
}
