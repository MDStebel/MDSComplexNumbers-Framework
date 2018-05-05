# MDSComplexNumbers Framework

## Initialize/create a New Complex Number:
var z = Complex() // 0 + 0𝒊

var w = Complex(2.5, -4.5) // 2.5 - 4.5𝒊

z = Complex(1.1, 0.9) // 1.1 + 0.9𝒊

## Complex Number Functions:
var sum = z + w // 3.6 - 3.6𝒊

var product = z * w // 6.8 - 2.7𝒊

var areEqual = (z == w) // false

var notEqual = (z != w) // true

var modulusOfComplexNumber = modulus(z) // 1.42126704035519

## Mixed Real and Complex Functions
var aDouble = Double.pi

var productOfDoubleAndComplex = aDouble * w // 7.85 - 14.14𝒊
