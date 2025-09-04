# Simple C++ Calculator

A basic C++ program that adds two integers entered by the user.

## Description

This program demonstrates fundamental C++ concepts including:
- Basic input/output operations using `cout` and `cin`
- Variable declaration and initialization
- Arithmetic operations
- User interaction through console

## Features

- Prompts user to enter two numbers
- Calculates and displays the sum of the two numbers
- Simple console-based interface

## Requirements

- C++ compiler (GCC, Clang, MSVC, etc.)
- Standard C++ library support

## How to Compile and Run

### Using GCC (Linux/macOS/Windows with MinGW)
```bash
g++ -o calculator main.cpp
./calculator
```

### Using Visual Studio (Windows)
1. Create a new C++ console application project
2. Replace the default code with the provided source
3. Build and run (Ctrl+F5)

### Using Code::Blocks or Dev-C++
1. Create a new C++ project
2. Add the source code to main.cpp
3. Build and run the project

## Usage

1. Run the program
2. When prompted, enter the first number and press Enter
3. When prompted, enter the second number and press Enter
4. The program will display the sum of the two numbers

## Example Output

```
Enter first number: 15
Enter second number: 25
The sum is: 40
```

## Code Structure

```cpp
#include <iostream>     // For input/output operations
using namespace std;    // To avoid writing std:: prefix

int main() {
    int num1, num2, sum;           // Variable declarations
    cout << "Enter first number: "; // Output prompt
    cin >> num1;                   // Read first number
    cout << "Enter second number: "; // Output prompt
    cin >> num2;                   // Read second number
    sum = num1 + num2;             // Calculate sum
    cout << "The sum is: " << sum << endl; // Display result
    return 0;                      // Exit successfully
}
```

## Learning Objectives

This program helps beginners understand:
- Basic C++ syntax and structure
- Variable declaration and usage
- Console input/output operations
- Arithmetic operations
- Program flow and execution

## Potential Enhancements

- Add input validation to handle non-integer inputs
- Support for floating-point numbers
- Multiple operations (subtraction, multiplication, division)
- Menu-driven interface for operation selection
- Error handling for edge cases

## License

This is a simple educational example and is free to use and modify.