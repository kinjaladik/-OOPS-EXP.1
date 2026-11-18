# -OOPS-EXP.1
C++ program to demonstrate data , types ,constants, variables operators and I/O

#include <iostream>

using namespace std;

int main() {
    int roll = 20;
    float marks = 85.5;
    char grade = 'A';
    const int total_marks = 100; // Fixed: use underscore instead of space
    int num;

    cout << "Enter a Number: ";
    cin >> num;

    int sum = num + roll;
    int difference = num - roll;
    int product = num * roll;

    cout << "\n--- Data Types & Constants ---\n";
    cout << "Roll No: " << roll << endl;
    cout << "Marks: " << marks << endl;
    cout << "Grade: " << grade << endl;
    cout << "Total Marks: " << total_marks << endl;

    cout << "\n--- Operators ---\n";
    cout << "Sum: " << sum << endl;
    cout << "Difference: " << difference << endl;
    cout << "Product: " << product << endl;
    
    return 0;
    }

    return 0;
}
