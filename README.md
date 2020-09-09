# unit-1
Repository for Unit 1 CS 2020

## Unit 1: A electronic hardware store

## Justification of solution

## Development

First test of the text based menu:

```.py
print("Welcome to Mr. Sakamoto's store :) \n")
name=input('Hey! Please enter your name: ')
print()
print("Nice to meet you {}".format (name))
print("This is the menu of our products:")
products = ["RAM","CPU","Motherboard","GPU","Display"]
for product in products:
  print(product)
print('\n')
for i in products:
  choose=input("Please imput the name of any product to see its price: ")
  choose=choose.upper()
  if choose=='RAM':
    print("The RAM has a price of $80 {} \n" .format(name))
  elif choose=='CPU':
    print('The CPU has a price of $150 {} \n'.format (name))
  elif choose=='MOTHERBOARD':
    print('The Motherboard has a price of $200 {} \n'.format (name))
  elif choose=='GPU':
    print('The GPU has a price of $100 {} \n'.format (name))
  elif choose=='DISPLAY':
    print('The Display has a price of $200 {} \n'.format (name))
print('We hope this information was useful, have a great day!')
```
### Task 2: Programming basics

```.py
string=input('plese input a word ')
print(string[2])
print(string[-2])
print(string[0:5])
print(string[:-2])
print(string[::2])
print(string[1::2])
print(string[::-1])
print(string[::-2])
print (len(string))

```
### Create a program that asks the user for 10 numbers and then shows those values ordered from smallest to largest.

```.py
print('input 10 numbers. Do not forget to add space: ', end='')
numbers=list(map(int, input().split()))
numbers.sort()
print(numbers)
```
