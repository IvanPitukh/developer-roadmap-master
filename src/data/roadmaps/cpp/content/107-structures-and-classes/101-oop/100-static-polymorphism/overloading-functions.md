# Function Overloading

Function overloading is a type of static polymorphism in C++ where multiple functions with the same name but different sets of parameters are defined in the same scope. This allows you to use the same function name for multiple tasks by providing different arguments while calling the function. The appropriate function to call is determined during compile-time based on the number and types of the arguments passed.

To overload a function, simply define another function with the same name but a different set of parameters. The compiler will automatically choose the correct function to call based on the provided arguments.

## Examples

Here's an example illustrating function overloading:

```cpp
#include <iostream>
using namespace std;

void print(int num) {
    cout << "Printing int: " << num << endl;
}

void print(double num) {
    cout << "Printing double: " << num << endl;
}

void print(char const *str) {
    cout << "Printing string: " << str << endl;
}

int main() {
    print(5);
    print(3.14);
    print("Hello, world!");

    return 0;
}
```

In this example, three overloaded functions named `print` are defined. They each take a different type of argument: `int`, `double`, and `char const *`. When calling `print()` with different arguments like `5`, `3.14`, or `"Hello, world!"`, the appropriate function is chosen based on the type of the provided argument.

The output of this program would be:

```
Printing int: 5
Printing double: 3.14
Printing string: Hello, world!
```

Keep in mind that the number of parameters and their types should be different for two functions to be overloaded.