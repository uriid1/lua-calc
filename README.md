# lua-calc
Command-line calculator written in LUA

```
Usage:
-i | --integer
    Converting the result to a decimal number

-c | --console-output
    Console output

Functions:
pi - Constant. Is Pi
% - Remainder

abs - Convert to a positive number

acos - Inverse cosine, result in radians
asin - Inverse sine, result in radians
atan - Arc tangent in radians

ceil - Rounding up
floor - Rounding down
round - Rounding to the nearest integer

sin - Sine in radians
cos - Cosine in radians
tan - Tangent in radians

deg - "From radians to degrees
rad - "From degrees to radians

log - log() returns the opposite value. exp(1) returns e
log10 - log10(val) Common logarithm
exp - exp(val) returns e (the base of natural logarithms) raised to the power of val
sqrt - Returns the square root

max - max(1, 2, 3) will return the maximum number from the given arguments
min - Returns the minimum number from the given arguments

sign - Will return 1, 0, -1 depending on the original argument
random - Generates a pseudo-random number, it is possible to specify a range (1, 10)

Examples:
calc '(30/100) * 100'
calc 'ceil(0.65) * 10'
calc 'sin(pi/2)'
calc 'deg(pi*2)'
calc -i 'abs(-100) / 2'
```

# Install
1) git clone https://github.com/uriid1/lua-calc/
2) cd lua-calc
3) chmod +x install
4) sh install
5) Done.

# Uninstall
sudo rm ~/.local/bin/calc