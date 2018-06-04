# MDSComplexNumbers
## Adds complex number support with complex math functions to iOS
To use this framework, add the MDSComplexNumbers.framework file to your Xcode project binaries. Make sure to add the line, "import MDSComplexNumbers" to each of your source code files that use the Complex number type and its methods.

## Functions & Examples
### Initialize/create a New Complex Number
var z = Complex()     // 0 + 0𝒊

var w = Complex(2.5, -4.5)    // 2.5 - 4.5𝒊

z = Complex(1.1, 0.9)     // 1.1 + 0.9𝒊

### Complex Number Functions
var sum = z + w     // 3.6 - 3.6𝒊

var product = z * w     // 6.8 - 2.7𝒊

var squareOfComplexNumber = sqr(z)    // 0.40 + 1.98𝒊

print(z - w)    // "-1.40 + 5.40𝒊"

var quotient = z / w    // 1.10 + 0.90𝒊

var areEqual = (z == w)     // false

var notEqual = (z != w)     // true

var modulusOfComplexNumber = modulus(z)     // 1.42126704035519

### Mixed Real and Complex Functions 
#### Double is first argument
var aDouble = Double.pi

print(aDouble * w)      // "7.85 - 14.14𝒊"

print(aDouble + z)      // "4.24 + 0.90𝒊"

print(aDouble - w)      // "0.64 + 4.50𝒊"
