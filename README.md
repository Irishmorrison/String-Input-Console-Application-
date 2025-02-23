# String-Input-Console-Application-

Here is the source code:

#include<iostream>
#include <string>

int main() {
    std::string string1, string2, result;

    // Loop to take input three times
    for (int i = 0; i < 3; ++i) {
        // Prompt for first string
        std::cout << "Enter the first string: ";
        std::getline(std::cin, string1);

        // Prompt for second string
        std::cout << "Enter the second string: ";
        std::getline(std::cin, string2);

        // Concatenate strings
        result = string1 + string2;

        // Print the result
        std::cout << "Concatenated Result: " << result << std::endl;
    }

    return 0;
}
