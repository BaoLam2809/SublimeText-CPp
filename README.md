# SublimeText-CPP
### Settings IDE for C++
### For young computer competitors

# 1 Main Fast On Sublime Name: ```mainf.sublime-snippet``` 
```<snippet>
<content><![CDATA[
// Code By ngkhacbaolam2809
//Enjoy =>>

#include <bits/stdc++.h>
using namespace std;
typedef long long ll;
typedef unsigned long long ull;
typedef double db;
typedef long double ld;
typedef vector<long long> vct;
typedef string str;
typedef pair<long long, long long> pr;
typedef set<long long> st;
typedef map<long long ,long long> mp;
#define endl '\n';
#define int64_t so;
#define db1(x) cout<<#x<<"="<<x<<'\n'
#define db2(x,y) cout<<#x<<"="<<x<<","<<#y<<"="<<y<<'\n'
#define db3(x,y,z) cout<<#x<<"="<<x<<","<<#y<<"="<<y<<","<<#z<<"="<<z<<'\n'
#define rep(i,n) for(int i=0;i<(n);++i)
#define repA(i,a,n) for(int i=a;i<=(n);++i)
#define repD(i,a,n) for(int i=a;i>=(n);--i)



/*bool check(){
    
}*/

void solve(){
    
}

int main(){
    ios_base::sync_with_stdio(false);
    cin.tie(NULL);
    freopen("test.INP","r",stdin);
    freopen("test.OUT","w",stdout);

    solve();

    return 0;
}
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
	 <tabTrigger>asdf</tabTrigger> 
	<!-- Optional: Set a scope to limit where the snippet will trigger -->
	 <scope>source.c++</scope> 
</snippet>
```
# 2 Build cpp On Sublime Name : ```CPP.sublime-build```
```{
	"encoding": "utf-8",
	"working_dir": "$file_path",
	"shell_cmd": "g++ -Wall -std=c++11 \"${file}\" -o \"${file_path}/${file_base_name}\"",
	"file_regex": "^(..[^:]*):([0-9]+):?([0-9]+)?:? (.*)$",
	"selector": "source.c++,source.c",

	"variants":
	[
		{   
			"name": "Run",
			"shell_cmd": "g++ -Wall -std=c++11 \"${file}\" -o \"${file_base_name}\" && start cmd /c \"\"${file_path}/${file_base_name}\" & pause\""
		}
	]
}
```

# 3 How to Make it : 
### 1 Download SublimeText 
#### https://www.sublimetext.com/download
### 2 Download MinGW
#### https://sourceforge.net/projects/mingw/
### 3 Set Var For C++ build
### 4 Build input and output


Finish ! 
# Or y Dont know
## https://blog.codingblocks.com/2019/setting-up-a-c-competitive-programming-environment/


