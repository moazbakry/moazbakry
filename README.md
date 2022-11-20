// C++ program of game of stones
#include <bits/stdc++.h>
using namespace std;
 
// Function that returns true if u win
bool checkWin(int n)
{
    if (n % 4 != 0)
        return true;
    return false;
}
 
// Driver code
int main()
{
    // n is number of stones
    int n = 4;
 
    if (checkWin(n))
        cout << "YES" << endl;
    else
        cout << "NO" << endl;
    return 0;
}
