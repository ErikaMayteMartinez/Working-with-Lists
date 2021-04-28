# Working-with-Lists

#for loops for pizza
pizzas = ['peperoni', 'olives', 'veggie']
for pizza in pizzas:
    print(pizza)

#adding a sentace to the pizza
pizzas = ['peperoni', 'olives', 'veggie']
for pizza in pizzas:
    print(f"{pizza.title()} pizza is the best!")
    #adding a sentance after the loop
print("I'm so hungry, I can eat a whole pizza!")

#for loops with animals
felines = ['cat', 'lion', 'panther']
for feline in felines:
    print(f" A {feline} would make a great pet.")
print(f"Any feline would make a great pet.")

#counting in range()
for value in range(1, 21):
    print(value)
    

#finding the min and max within the range, and the sum of all numbers within the range
digits = range(1, 21)
print(min(digits))
print(max(digits))
print(sum(digits))

#odd numbers; the last number '2" within the range indicates to the program to add 2 to the previous number, 
#to get to the next odd number in the sequence
odd_numbers = list(range(1, 21, 2))
print(odd_numbers)
even_numbers = list(range(2, 21, 2))
print(even_numbers)

#multiples of 3
multiples = []
for value in range(1, 21):
    multiples.append(value*3)
print(multiples)

#cubes
cubes = []
for value in range(1, 11):
    cubes.append(value**3)
print(cubes)

#list compreshion
cubes = [value**3 for value in range(1,11)]
print(cubes)

#slicing lists: listing first three items
golden_girls= ['rose', 'blanche', 'dorothy', 'sophia', 'cheesecake']
print("The characters in the Golden Girls are:")
for golden_girl in golden_girls[0:3]:
    print(golden_girl.title())

#slicing lists: listing middle three items
print("The unrelated characters in the Golden Girls are:")
for golden_girl in golden_girls[1:4]:
    print(golden_girl.title())

#slicing lists: listing second last two items
print("The mother daughter duo in the Golden Girls are:")
for golden_girl in golden_girls[2:4]:
    print(golden_girl.title())

#slicing lists: listing second last two items
print("The Golden Girls' favorite dessert is:")
for golden_girl in golden_girls[-1:]:
    print(golden_girl.title())

#adding items to the list
golden_foods = golden_girls[:]
golden_girls.append('carrot cake')
golden_foods.append('pasta')
print("The Golden Girls also eat:")
for golden_girl in golden_girls[-2:]:
    print(golden_girl.title())
print("But the Golden Girls especially indulge in:")
for golden_food in golden_foods[-2:]:
    print(golden_food.title())

#tuple
sizzlers = ('salad', 'soup', 'wings', 'nachos', 'ice cream')
print("Sizzler offers the following options in their buffet:")
for sizzler in sizzlers:
    print(sizzler)
sizzlers = ('salad', 'soup', 'rotisserie chicken', 'beans', 'ice cream')
print("However, Sizzler changed their main course options in their buffet:")
for sizzler in sizzlers:
    print(sizzler)
