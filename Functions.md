### Functions in C++
---
### With argument without return.
```c++
#include <iostream>
void add(int x, int y);
using namespace std;
int main() {
    int a , b;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    add(a, b);
    return 0;
}
void add(int x, int y) {
    int sum = x + y;
    cout << "The sum of " << x << " and " << y << " is: " << sum << endl;
}
```
---