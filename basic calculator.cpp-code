#include <iostream>
using namespace std;

int main() {
    double num1, num2; // These are the two numbers on which operations will be applied
    char op; // Stores the operation to be applied
    
    // Input first number
    cout << "Enter your first number: ";
    cin >> num1;
    
    // Input second numberF
    cout << "Enter your second number: ";
    cin >> num2;
    
    // Input operation
    cout << "Enter the operation (+, -, *, or /): ";ٖ
    cin >> op;

    double result; // The final result after applying the operation
    bool validOperation = true;
    
    // Switch statement to apply the operation
    switch (op) {
        case '+':
            result = num1 + num2;
            break;
            
        case '-':
            result = num1 - num2;
            break;
            
        case '*':
            result = num1 * num2;
            break;
            
        case '/':
            if (num2 != 0) {
                result = num1 / num2;
            } else {
                cout << "Error: Division by zero!" << endl;
                validOperation = false;
            }
            break;
            
        default:
            cout << "Error: Invalid operation!" << endl;
            validOperation = false;
    }
    
    // Print result only if the operation was valid
    if (validOperation) {
        cout << "Result: " << result << endl;
    }
    
    return 0; // Program ends
}
