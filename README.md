# Celsius to Fahrenheit Conversion

This repository contains a simple Swift program that converts a temperature from Celsius to Fahrenheit. The program demonstrates the basic arithmetic operation required for temperature conversion and prints the result in a readable format.

## Formula

The formula used for conversion is:
°F = (°C × 9 / 5) + 32

For example, if the temperature in Celsius is `23.4°C`, the equivalent temperature in Fahrenheit will be `74.12°F`.

## Code Example

```swift
import Cocoa

// MARK: Celsius to Fahrenheit conversion

// Define a constant for temperature in Celsius
let celsius = 23.4

// Convert Celsius to Fahrenheit
let fahrenheit = (celsius * 9 / 5) + 32

// Print the results
print("Celsius: \(celsius)°C -> Fahrenheit: \(fahrenheit)°F")
```
## Usage
1. Clone the repository: git clone https://github.com/your-username/CelsiusToFahrenheitConversion.git
2. Open the file in your Swift-compatible editor or run it in a Swift environment.
3. Run the program to see the output for the conversion from Celsius to Fahrenheit.

## Output

Running the program will produce an output similar to:
```swift
Celsius: 23.4°C -> Fahrenheit: 74.12°F
```
## License

This project is licensed under the MIT License - see the LICENSE file for details.
