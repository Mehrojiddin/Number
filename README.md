# Number
# Number Methods and Properties
Primitive values (like 3.14 or 2014), cannot have properties and methods (because they are not objects).

But with JavaScript, methods and properties are also available to primitive values, because JavaScript treats primitive values as objects when executing methods and properties.

## The toString() Method
The toString() method returns a number as a string.

All number methods can be used on any type of numbers (literals, variables, or expressions):

## The toExponential() Method
toExponential() returns a string, with a number rounded and written using exponential notation.

A parameter defines the number of characters behind the decimal point:

## The toFixed() Method
toFixed() returns a string, with the number written with a specified number of decimals:

## The toPrecision() Method
toPrecision() returns a string, with a number written with a specified length:


## The valueOf() Method
valueOf() returns a number as a number.


# Converting Variables to Numbers
There are 3 JavaScript methods that can be used to convert variables to numbers:

The Number() method
The parseInt() method
The parseFloat() method
These methods are not number methods, but global JavaScript methods.

# Global JavaScript Methods
JavaScript global methods can be used on all JavaScript data types.

These are the most relevant methods, when working with numbers:

Method	Description
Number()	Returns a number, converted from its argument.
parseFloat()	Parses its argument and returns a floating point number
parseInt()	Parses its argument and returns an integer

### The Number() Method
Number() can be used to convert JavaScript variables to numbers:


### The Number() Method Used on Dates
Number() can also convert a date to a number.


### The parseInt() Method
parseInt() parses a string and returns a whole number. Spaces are allowed. Only the first number is returned:

### The parseFloat() Method
parseFloat() parses a string and returns a number. Spaces are allowed. Only the first number is returned:

### Number Properties

Property	        Description
MAX_VALUE	        Returns the largest number possible in JavaScript
MIN_VALUE	        Returns the smallest number possible in JavaScript
POSITIVE_INFINITY	Represents infinity (returned on overflow)
NEGATIVE_INFINITY	Represents negative infinity (returned on overflow)
NaN	                Represents a "Not-a-Number" value


### JavaScript MIN_VALUE and MAX_VALUE
MAX_VALUE returns the largest possible number in JavaScript.
