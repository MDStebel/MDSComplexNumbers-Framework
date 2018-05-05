# MDSComplexNumbers Framework

## Initialize/create a New Complex Number:
var z = Complex() // 0 + 0i

var w = Complex(2.5, -4.5) // 2.5 - 4.5i

z = Complex(1.1, 0.9) // 1.1 + 0.9i

## Complex Number Functions:
var sum = z + w // 3.6 - 3.6i

var product = z * w // 6.8 - 2.7i

var areEqual = (z == w) // false

var notEqual = (z != w) // true

var modulusOfComplexNumber = modulus(z) // 1.42126704035519

## Mixed Real and Complex Functions
var aDouble = Double.pi

var productOfDoubleAndComplex = aDouble * w // 7.85 - 14.14𝒊
