# lua-calc
Simple LUA command-line calculator

Constans: <br/>
pi - Constant. Is Pi <br/>
huge - Constant. +infinity <br/>

Functions: <br/>
sign - Will return 1, 0, -1 depending on the original argument <br/>
deg - From radians to breasts  <br/>
ceil - Rounding up <br/>
sin - Sine in radians <br/>
abs - Convert to a positive number <br/>
random - Generates a pseudo-random number, it is possible to specify a range (1, 10) <br/>
sqrt - Returns the square root <br/>
tan - Tangent in radians <br/>
floor - Rounding down <br/>
min - Returns the minimum number from the given arguments <br/>
atan - Arc tangent in radians <br/>
asin - Inverse sine, result in radians <br/>
cos - Cosine in radians <br/>
acos - Inverse cosine, result in radians <br/>
max - max(1, 2, 3) will return the maximum number from the given arguments <br/>
rad - From chests to radians <br/>
exp - exp(val) returns e (the base of natural logarithms) raised to the power of val <br/>
log - log() returns the opposite value. exp(1) returns e <br/>
round - Rounding to the nearest integer <br/>

Examples: <br/>
calc '(30/100) * 100' <br/>
calc 'ceil(0.65) * 10' <br/>
calc 'sin(pi/2)' <br/>
calc 'abs(-100) / 2' <br/>
calc 'deg(pi*2)' <br/>

# Install
1) git clone https://github.com/uriid1/lua-calc/
2) cd lua-calc
3) chmod +x install
4) sudo ./install
5) Done! Delele lua-calc folder.

# Uninstall
sudo rm /usr/bin/calc