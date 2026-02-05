# Object-oriented-programing-with-c++
# Q1. Write a C++ program that takes two integers as input from the user and displays their sum.
    #include <iostream>
    int main(){
    int a,b,c;
    std::cout<<"\nEnter a  and b";
    std::cin>>a>>b;
    c=a+b;
    std::cout<<c;
    return 0;
    }
# Q2. Write a C++ program to check whether a given number is even or odd.
    #include <iostream>
    int main()
    {
    int a;
    std::cout << "Enter a number: ";
    std::cin >> a;

    if (a % 2 == 0) {
        std::cout << "Even number\n";
    } else {
        std::cout << "Odd number\n";
    }
    return 0;
    }
# Q3. Write a C++ program to print all numbers from 1 to n, where n is a number entered by the user.
    #include <iostream>
    using namespace std;

    int main() {
    int n;
    cin >> n;
    for (int i = 1; i <= n; i++)
    {
    cout << i << " ";
    }
    return 0;
    }
# Q4. To print sum of n natural numbers
    #include <iostream>
    using namespace std;
    
    int main(int argc, char *argv[])
    {
        int n, sum = 0;
    
        if (argc > 1)
            n = atoi(argv[1]);
        else {
            cout << "Enter n: ";
            cin >> n;
        }
    
        for (int i = 1; i <= n; i++)
            sum += i;
    
        cout << "Sum = " << sum;
        return 0;
    }
# WAP to swap two values 
    #include <iostream>
    void swap(std::string &a, std::string &b){
        std::string temp;
        temp=a;
        a=b;
        b=temp;
    }
    int main(){
    std::string x = "Kool aid";
    std::string y = "Water";
    std::string temp;
    swap(x,y);
    std::cout<<x <<"\n";
    std::cout<<y <<"\n";
    }
## Outuput
    Water
    Kool aid
