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
