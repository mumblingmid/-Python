# HW exercises 1, 2, 3, 9, 10, 11, and 12

## Exercise 1:Print

### A
*The goal of this exercise is to print "Hello World" to the screen.*

```
print("Hello World")

### B
*Assign "Hello World!" to the variable my_text.*

```
my_text="Hello World!"
print(my_text)

## Exercise 2: Variables

### A 

*Assign a number to the variable: glass_of_water*

```
glass_of_water= 3

print("I drank", glass_of_water, "glasses of water today.")

### B

*Place the variable: glass_of_water inside the print function and observe what happens.*

```
glass_of_water=3

glass_of_water=glass_of_water + 1

print (glass_of_water)

## Exercise 3: Data type Exercise

### A

*Assign an integer to the variable, then print it.*

```
men_stepped_on_the_moon= 12
print()

### B

*string example*

```
my_reason_for_coding= "Programming robots."
print(my_reason_for_coding)

### C

*assign a new value to our variable*

```
global_mean_sea_level_2018=21

global_mean_sea_level_2018= global_mean_sea_level_2018 = 21.36

print(global_mean_sea_level_2018)


## Exercise 9: Strings

### A

*Assign the string to the variable in the exercise. "It's always darkest before dawn."*

```
str="It's always darkest before dawn."

print(str)

### B

*Create a new string, by using first, second and last characters of the string.*

```
str="It's always darkest before dawn."

ans_1= ans_1 = str[0]+str[1]+str[-1]

print(ans_1)

### C

*Replace the (.) with (!)*

```
str="It's always darkest before dawn."
str = str.replace(".", "!")
print(str)

## Exercise 10: len function

### A

*The goal of this exercise is to use the len() function find out how many items are in the list.*

```
lst=[11, 10, 12, 101, 99, 1000, 999]

answer_1=len(lst)


print(answer_1)

## Exercise 11: Sort

### A
*Sort the list in ascending order with .sort() method.*

```
lst=[11, 100, 99, 1000, 999]
lst.sort()
print(lst)

### B
*Sort the countries in alphabetic order.*

lst=["Ukraine", "Japan", "Canada", "Kazakhstan", "Taiwan", "India", "Belize"]

```
lst.sort(reverse = False)

print(lst)

### C

*sort the list in descending order with .sort() method.*
lst=[11, 100, 101, 999, 1001]

```
lst.sort(reverse = True)

print(lst)

## Exercise 12: Pop Exercise

### A
*Pop the last item of the list below.*

lst=[11, 100, 99, 1000, 999]

```
popped_item= lst.pop()
 
print(popped_item)
print(lst)

### B
*Remove "broccoli" from the list using .pop and .index methods.*

lst=["milk", "banana", "eggs", "bread", "broccoli", "lemons"]

```
a=lst.index("broccoli")
item=lst.pop(a)

print(lst, item)

### C
*Save Italy's GDP in a separate variable and remove it from the dictionary.*

GDP_2018={"US": 21, "China": 16, "Japan": 5, "Germany": 4, "India": 3, "France": 3, "UK": 3, "Italy": 2}

```
italy_gdp=italy_gdp = GDP_2018.pop("Italy")

print(GDP_2018)
print(italy_gdp, "trillion USD")
