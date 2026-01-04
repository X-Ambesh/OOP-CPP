# Object-oriented-programing-with-c++
# Q1. Write a C++ program that takes two integers as input from the user and displays their sum.
a. Sum if two numbers

Input (code)

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
Input (code)

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
