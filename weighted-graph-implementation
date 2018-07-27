#include <bits/stdc++.h>
using namespace std;
 
const int N = 4;
vector<pair<int, int> > adj[N];
 
int main(){
        // The following two lines are for a faster io with cin and cout
    ios_base::sync_with_stdio(false);
    cin.tie(NULL);
    // build the graph
    adj[0].push_back(make_pair(1, 389));
    adj[0].push_back(make_pair(2, 405));
 
    adj[1].push_back(make_pair(0, 389));
    adj[1].push_back(make_pair(3, 818));
 
    adj[2].push_back(make_pair(0, 405));
    adj[2].push_back(make_pair(3, 765));
 
    adj[3].push_back(make_pair(1, 818));
    adj[3].push_back(make_pair(2, 765));
 
 
    // print the graph
    int v, w;
 
    for (int u=0; u<N; u++) {
        cout << "Node u=" << u << " has the following neighbors:\n";
 
        for (pair<int,int> p : adj[u]) {
            v = p.first;
            w = p.second;
            cout << "\tNode v=" << v << " with edge weight w=" << w << "\n";
        }
 
        cout << "\n";
    }
 
    return 0;
}
