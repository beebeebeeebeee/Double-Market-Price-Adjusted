# Double-Market-Price-Adjusted

This is the adjusted version of Double-Market-Price

Expectation: original price * 2 - 0.01

Example:
- original price = 14.19
- target price = 28.37

### changes

- remove all round down logic when calculating the price
- -$0.01 after doubling the price

### methodology

modify original .dll file using dnSpy
