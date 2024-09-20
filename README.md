# Basic-codes
// Calculate the sum of numbers from 1 to N....
#include <iostream>
using namespace std;
int sum(int n, int s)
{
    for (int i = 1; i <= n; i++)
    {
        s += i;
    }
    return s;
}
int main()
{
    int n;
    cout << "Enter the number : ";
    cin >> n;
    int s = 0;
    sum(n, s);
    cout << "The sum of numbers from 1 to " << n << " is : " << sum(n, s) << endl;

    return 0;
}
