///          Bismillahir Rahmanir Rahim
///         .......Tanvir Ahmmad........
///     Islamic University,CSE,2017-18 session

#include<bits/stdc++.h>
using namespace std;
typedef long long ll;
int main()
{
    char s[1000003];
    ll ca=0,tst;
    while(scanf("%s %lld", s, &tst) == 2)
    {
        ll a,b;
        printf("Case %lld:\n",++ca);
        while(tst--)
        {
            cin>>a>>b;
            ll mid=(a+b)/2,flag=0;
            for(ll i=min(a,b),j=max(a,b);i<mid,j>mid;i++,j--)
            {
                if(s[mid]!=s[i] || s[mid]!=s[j])
                {
                    flag=1;
                    break;
                }
            }
            if(flag) cout<<"No"<<endl;
            else cout<<"Yes"<<endl;
        }
    }
    return 0;
}
