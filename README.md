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

### Juan Quintero Task 2: Programming basics
### Task 2: Programming basics exercises in Snakify:

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

```.py
n1 = int(input('Please enter a number: '))
n2 = int(input('Please enter another number: '))
  
for i in range(n1,n2 + 1):
  print(i, end=" ")
```

## Create a program that asks the user for 10 numbers and then shows those values ordered from smallest to largest.

```.py
print('input 10 numbers. Do not forget to add space: ', end='')
numbers=list(map(int, input().split()))
numbers.sort()
print(numbers)
```

![WhatsApp Image 2020-09-11 at 2 59 33 PM (1)](https://user-images.githubusercontent.com/70176375/92970364-2ab9e200-f444-11ea-9150-cb87bf0d6bee.jpeg)

![WhatsApp Image 2020-09-11 at 2 59 33 PM](https://user-images.githubusercontent.com/70176375/92970499-62c12500-f444-11ea-8197-6dabc6d92229.jpeg)

