# MyProject
#include <bits/stdc++.h>

using namespace std;

int main()
{
   int n;
   cin>>n;
   int cnt = 0;
   while(cnt<=n)
   {
       if (cnt % 8 == 0 || cnt % 3 == 0 && cnt % 4 == 0)
           cout << cnt << " ";
       cnt++;
   }
        return 0;

}
