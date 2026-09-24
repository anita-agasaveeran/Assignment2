# Outputs: Agasaveeran_final_Intro_to_Python_for_Machine_Learning


## Code cell 1

```python
import this
```

```text
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```


## Code cell 2

```python
# EXAMPLE OF CREATING A VARIABLE

# We use # to add comment, it won’t run or affect the code
# You use = to assign a value to the name of the variable.
# Each code starts on the new line. No semicolon or {}
# Python is awesome. You do not need to provide the data type of variable when creating it.

int_var = 1
str_var = 'Hundred'
```


## Code cell 3

```python
int_var = 10
float_var = 12.8

type(int_var)
```

```text
int
```


## Code cell 4

```python
type(float_var)
```

```text
float
```


## Code cell 5

```python
# Numeric Operations

# Addition

1 + 100
```

```text
101
```


## Code cell 6

```python
# Multiplication

1 * 100
```

```text
100
```


## Code cell 7

```python
# Division

1 / 100
```

```text
0.01
```


## Code cell 8

```python
# Floor division

7 // 2
```

```text
3
```


## Code cell 9

```python
# Modular (%)
# This is the remainder or a value remaining after dividing two numbers
# 100 / 1 = 100, remainder is 0

100 % 1
```

```text
0
```


## Code cell 10

```python
1 % 100
```

```text
1
```


## Code cell 11

```python
10 % 2
```

```text
0
```


## Code cell 12

```python
# Powers
# 1 power any number is 1 always

1 ** 100
```

```text
1
```


## Code cell 13

```python
2 ** 2
```

```text
4
```


## Code cell 14

```python
# We use print() to display the results of the operations or a variable

print(1 + 100)
```

```text
101
```


## Code cell 15

```python
str_var = 'One'
str_var2 = 'Hundred'
```


## Code cell 16

```python
str_var + str_var2
```

```text
'OneHundred'
```


## Code cell 17

```python
str_var + ' ' + 'and' + ' '+ str_var2 + '.'
```

```text
'One and Hundred.'
```


## Code cell 18

```python
# We can use print() to display a string

print(" This is a string")
```

```text
 This is a string
```


## Code cell 19

```python
# We can also compare strings to check whether they are similar.
# If they are similar, case by case, comparison operator returns true. Else false

"A string" == "a string"
```

```text
False
```


## Code cell 20

```python
"A string" == "A string"
```

```text
True
```


## Code cell 21

```python
sentence = 'This IS A String'
```


## Code cell 22

```python
# Case capitalization
# It return the string with first letter capitalized and the rest being lower cases.

sentence.capitalize()
```

```text
'This is a string'
```


## Code cell 23

```python
# Given a string, convert it into title (each word is capitalized)

sentence_2 = 'this is a string to be titled'
sentence_2.title()
```

```text
'This Is A String To Be Titled'
```


## Code cell 24

```python
# Converting the string to upper case

sentence.upper()
```

```text
'THIS IS A STRING'
```


## Code cell 25

```python
# Converting the string to upper case

sentence.lower()
```

```text
'this is a string'
```


## Code cell 26

```python
# Splitting the string

sentence.split()
```

```text
['This', 'IS', 'A', 'String']
```


## Code cell 27

```python
stri = "This movie was awesome"
stri.replace('movie', 'project')
```

```text
'This project was awesome'
```


## Code cell 28

```python
# In the following string, replace all spaces with `%20'

stri_2 = "The future is great"
stri_2.replace(' ', '%20')
```

```text
'The%20future%20is%20great'
```


## Code cell 29

```python
# Creating a list

week_days = ['Mon', 'Tue', 'Wed', 'Thur','Fri']
even_numbers = [2, 4, 6, 8, 10]
mixed_list = ['Mon', 1, 'Tue', 2, 'Wed', 3]

# Displaying elements of a list
print(week_days)
```

```text
['Mon', 'Tue', 'Wed', 'Thur', 'Fri']
```


## Code cell 30

```python
# Creating a list with range()

nums = range(5)

for i in nums:
    print(i)
```

```text
0
1
2
3
4
```


## Code cell 31

```python
# Accessing the first elements of the list

week_days[0]
```

```text
'Mon'
```


## Code cell 32

```python
even_numbers[2]
```

```text
6
```


## Code cell 33

```python
# Getting the last element of the list

print(even_numbers[-1])
```

```text
10
```


## Code cell 34

```python
# Get the elements from index 0 to 2. Index 2 is not included.

week_days = ['Mon', 'Tue', 'Wed', 'Thur','Fri']
week_days[0:2]
```

```text
['Mon', 'Tue']
```


## Code cell 35

```python
# Get elements from the last fourth elements to the first
# -1 starts at the last element 'Fri', -2 second last element `Thur'..... -4 to 'Tue'

week_days[-4:]
```

```text
['Tue', 'Wed', 'Thur', 'Fri']
```


## Code cell 36

```python
# Get all elements up to the fourth index

week_days[:4]
```

```text
['Mon', 'Tue', 'Wed', 'Thur']
```


## Code cell 37

```python
# Get all elements from the second to the last index

week_days[2:]
```

```text
['Wed', 'Thur', 'Fri']
```


## Code cell 38

```python
week_days[:]
```

```text
['Mon', 'Tue', 'Wed', 'Thur', 'Fri']
```


## Code cell 39

```python
names = ['James', 'Jean', 'Sebastian', 'Prit']
names
```

```text
['James', 'Jean', 'Sebastian', 'Prit']
```


## Code cell 40

```python
# Change 'Jean' to 'Nyandwi' and 'Sebastian' to 'Ras'

names[1:3] = ['Nyandwi', 'Ras']
names
```

```text
['James', 'Nyandwi', 'Ras', 'Prit']
```


## Code cell 41

```python
# Change 'Prit' to Sun

names[-1] = 'Sun'
names
```

```text
['James', 'Nyandwi', 'Ras', 'Sun']
```


## Code cell 42

```python
# Change `James` to ``Francois`

names[0] = 'Francois'
names
```

```text
['Francois', 'Nyandwi', 'Ras', 'Sun']
```


## Code cell 43

```python
# Delete Nyandwi in names list

del names[1]
names
```

```text
['Francois', 'Ras', 'Sun']
```


## Code cell 44

```python
names = ['James', 'Jean', 'Sebastian', 'Prit']
names.pop(2)
names
```

```text
['James', 'Jean', 'Prit']
```


## Code cell 45

```python
names = ['James', 'Jean', 'Sebastian', 'Prit']
names.remove('James')
names
```

```text
['Jean', 'Sebastian', 'Prit']
```


## Code cell 46

```python
# Adding the new elements in list

names = ['James', 'Jean', 'Sebastian', 'Prit']
names.append('Jac')
names.append('Jess')
names
```

```text
['James', 'Jean', 'Sebastian', 'Prit', 'Jac', 'Jess']
```


## Code cell 47

```python
# Given a list names, use for loop to display its elements

names = ['James', 'Jean', 'Sebastian', 'Prit']

for name in names:
    print(name)
```

```text
James
Jean
Sebastian
Prit
```


## Code cell 48

```python
# Given a list nums, add 1 to the first element, 2 to the second, 3 to 3rd element, 4 to 4th element
# Example: nums = [1,2,3,6] will be nums_new = [2,4,6,10]

nums = [1, 2, 3, 6]
nums_new = []

for i in range(len(nums)): #len(nums) gives the length of the list
    num = nums[i] + i + 1
    nums_new.append(num)

nums_new
```

```text
[2, 4, 6, 10]
```


## Code cell 49

```python
# Concatenating two lists

a = [1,2,3]
b = [4,5,6]

c = a + b

c
```

```text
[1, 2, 3, 4, 5, 6]
```


## Code cell 50

```python
# We can also use * operator to repeat a list a number of times

[None] * 5
```

```text
[None, None, None, None, None]
```


## Code cell 51

```python
[True] * 4
```

```text
[True, True, True, True]
```


## Code cell 52

```python
[1,2,4,5] * 2
```

```text
[1, 2, 4, 5, 1, 2, 4, 5]
```


## Code cell 53

```python
# Creating a list in other list

nested_list = [1,2,3, ['a', 'b', 'c']]


# Get the ['a', 'b', 'c'] from the nested_list

nested_list[3]
```

```text
['a', 'b', 'c']
```


## Code cell 54

```python
# Indexing and slicing a nested list is quite similar to normal list

nested_list[1]
```

```text
2
```


## Code cell 55

```python
# Sorting a list with sort()

even_numbers = [2,14,16,12,20,8,10]

even_numbers.sort()

even_numbers
```

```text
[2, 8, 10, 12, 14, 16, 20]
```


## Code cell 56

```python
# Reversing a string with reverse()

even_numbers.reverse()
even_numbers
```

```text
[20, 16, 14, 12, 10, 8, 2]
```


## Code cell 57

```python
# Adding other elements to a list with append()

even_numbers = [2,14,16,12,20,8,10]

even_numbers.append(40)
even_numbers
```

```text
[2, 14, 16, 12, 20, 8, 10, 40]
```


## Code cell 58

```python
# Removing the first element of a list

even_numbers.remove(2)
even_numbers
```

```text
[14, 16, 12, 20, 8, 10, 40]
```


## Code cell 59

```python
## Return the element of the list at index x

even_numbers = [2,14,16,12,20,8,10]

## Return the item at the 1st index

even_numbers.pop(1)
```

```text
14
```


## Code cell 60

```python
# pop() without index specified will return the last element of the list

even_numbers = [2,14,16,12,20,8,10]
even_numbers.pop()
```

```text
10
```


## Code cell 61

```python
# Count a number of times an element appear in a list

even_numbers = [2,2,4,6,8]
even_numbers.count(2)
```

```text
2
```


## Code cell 62

```python
# We can convert a string into list

stri = 'Apple'

list(stri)
```

```text
['A', 'p', 'p', 'l', 'e']
```


## Code cell 63

```python
# Splitting a string produces a list of individual words

stri_2 = "List and Strings"
stri_2.split()
```

```text
['List', 'and', 'Strings']
```


## Code cell 64

```python
stri_3 = "state-of-the-art"

stri_3.split('-')
```

```text
['state', 'of', 'the', 'art']
```


## Code cell 65

```python
# Creating a dictionary

countries_code = dict()
print(countries_code)
```

```text
{}
```


## Code cell 66

```python
type(countries_code)
```

```text
dict
```


## Code cell 67

```python
# Adding items to the empty dictionary.

countries_code["United States"] = 1
```


## Code cell 68

```python
countries_code
```

```text
{'United States': 1}
```


## Code cell 69

```python
countries_code = {
        "United States": 1,
        "China": 86,
        "Rwanda":250,
        "Germany": 49,
        "India": 91,
}

countries_code
```

```text
{'United States': 1, 'China': 86, 'Rwanda': 250, 'Germany': 49, 'India': 91}
```


## Code cell 70

```python
countries_code['Australia'] = 61
countries_code
```

```text
{'United States': 1,
 'China': 86,
 'Rwanda': 250,
 'Germany': 49,
 'India': 91,
 'Australia': 61}
```


## Code cell 71

```python
# Getting the code of Rwanda

countries_code["Rwanda"]
```

```text
250
```


## Code cell 72

```python
"India" in countries_code
```

```text
True
```


## Code cell 73

```python
# Should be False

"Singapore" in countries_code
```

```text
False
```


## Code cell 74

```python
# Getting the keys and the values and items of the dictionary

dict_keys = countries_code.keys()
dict_values = countries_code.values()
dict_items = countries_code.items()

print(f"Keys: {dict_keys}\n Values:{dict_values}\n Items:{dict_items}")
```

```text
Keys: dict_keys(['United States', 'China', 'Rwanda', 'Germany', 'India', 'Australia'])
 Values:dict_values([1, 86, 250, 49, 91, 61])
 Items:dict_items([('United States', 1), ('China', 86), ('Rwanda', 250), ('Germany', 49), ('India', 91), ('Australia', 61)])
```


## Code cell 75

```python
# Get the value of the Australia

countries_code.get('Australia')
```

```text
61
```


## Code cell 76

```python
# In case a provided key is absent....

countries_code.get('UK', 41)
```

```text
41
```


## Code cell 77

```python
stri = 'aaaaajjj222@@@sss^^^888'

counts = [0] * 128 # Create a list of 128 elements, initially each character count is 0.

for c in stri:
    c_num = ord(c)

    counts[c_num] = counts[c_num] + 1

counts
```

```text
[0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 5,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 3,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0,
 0]
```


## Code cell 78

```python
stri = "jdjjdjdjdjjdjdjdj"

counts_dict = {}

for c in stri:
    if c not in counts_dict:
        counts_dict[c] = 1

    else:
        counts_dict[c] += 1

print(counts_dict)
```

```text
{'j': 10, 'd': 7}
```


## Code cell 79

```python
stri = input(str) #input must be a string

char_count = {}

for c in stri:
    char_count[c] = char_count.get(c,0) + 1

print(char_count)
```

```text
{'m': 1, 'a': 2, 'c': 1, 'h': 1, 'i': 2, 'n': 3, 'e': 2, ' ': 1, 'l': 1, 'r': 1, 'g': 1}
```


## Code cell 80

```python
countries_code
```

```text
{'United States': 1,
 'China': 86,
 'Rwanda': 250,
 'Germany': 49,
 'India': 91,
 'Australia': 61}
```


## Code cell 81

```python
for country in countries_code:
    print(country)
```

```text
United States
China
Rwanda
Germany
India
Australia
```


## Code cell 82

```python
for country, code in countries_code.items():
    print(country, code)
```

```text
United States 1
China 86
Rwanda 250
Germany 49
India 91
Australia 61
```


## Code cell 83

```python
countries_code.setdefault("UK", 41)
```

```text
41
```


## Code cell 84

```python
countries_code
```

```text
{'United States': 1,
 'China': 86,
 'Rwanda': 250,
 'Germany': 49,
 'India': 91,
 'Australia': 61,
 'UK': 41}
```


## Code cell 85

```python
stri = input(str) #input must be a string

char_count = {}

for c in stri:
    char_count.setdefault(c,0) #If character doesn't exist in char_count, add it and set it to 0
    char_count[c] += 1

print(char_count)
```

```text
{'m': 1, 'a': 2, 'c': 1, 'h': 1, 'i': 2, 'n': 3, 'e': 2, ' ': 1, 'l': 1, 'r': 1, 'g': 1}
```


## Code cell 86

```python
tup = (1,4,5,6,7,8)
```


## Code cell 87

```python
# Indexing

tup[4]
```

```text
7
```


## Code cell 88

```python
## Tuples are not changeable. Running below code will cause an error

# tup[2] = 10
```


## Code cell 89

```python
# You can not also add other values to the tuple. This will be error
#tup.append(12)
```


## Code cell 90

```python
set_1 = {1,2,3,4,5,6,7,8}

set_1
```

```text
{1, 2, 3, 4, 5, 6, 7, 8}
```


## Code cell 91

```python
set_2 = {1,1,2,3,5,3,2,2,4,5,7,8,8,5}
set_2
```

```text
{1, 2, 3, 4, 5, 7, 8}
```


## Code cell 92

```python
# List Vs Set

odd_numbers = [1,1,3,7,9,3,5,7,9,9]

print("List:{}".format(odd_numbers))

print("********")

set_odd_numbers = {1,1,3,7,9,3,5,7,9,9}

print("Set:{}".format(set_odd_numbers))
```

```text
List:[1, 1, 3, 7, 9, 3, 5, 7, 9, 9]
********
Set:{1, 3, 5, 7, 9}
```


## Code cell 93

```python
## Greater than
100 > 1
```

```text
True
```


## Code cell 94

```python
## Equal to

100 == 1
```

```text
False
```


## Code cell 95

```python
## Less than

100 < 1
```

```text
False
```


## Code cell 96

```python
## Greater or equal to

100 >= 1
```

```text
True
```


## Code cell 97

```python
## Less or equal to

100 <= 1
```

```text
False
```


## Code cell 98

```python
'Intro to Python' == 'intro to python'
```

```text
False
```


## Code cell 99

```python
'Intro to Python' == 'Intro to Python'
```

```text
True
```


## Code cell 100

```python
100 == 100 and 100 == 100
```

```text
True
```


## Code cell 101

```python
100 <= 10 and 100 == 100
```

```text
False
```


## Code cell 102

```python
100 == 10 or 100 == 100
```

```text
True
```


## Code cell 103

```python
100 == 10 or 100 == 10
```

```text
False
```


## Code cell 104

```python
not 1 == 2
```

```text
True
```


## Code cell 105

```python
not 1 == 1
```

```text
False
```


## Code cell 106

```python
if 100 < 2:

  print("As expected, no thing will be displayed")
```


## Code cell 107

```python
if 100 > 2:

  print("As expected, no thing will be displayed")
```

```text
As expected, no thing will be displayed
```


## Code cell 108

```python
if 100 < 2:

  print("As expected, no thing will be displayed")

else:
  print('Printed')
```

```text
Printed
```


## Code cell 109

```python
# Let's assign a number to a variable name 'jean_age' and 'yannick_age'

john_age = 30
luck_age = 20

if john_age > luck_age:
  print("John is older than Luck")

else:
  print(" John is younger than Luck")
```

```text
John is older than Luck
```


## Code cell 110

```python
# Let's use multiple conditions

john_age = 30
luck_age = 20
yan_age = 30

if john_age < luck_age:
  print("John is older than Luck")

elif yan_age == luck_age:
  print(" Yan's Age is same as Luck")

elif luck_age > john_age:
  print("Luck is older than John")

else:
  print("John's age is same as Yan")
```

```text
John's age is same as Yan
```


## Code cell 111

```python
# Example 1: Return 'Even' if below num is 'Even' and `Odd` if not.

num = 45

'Even' if num % 2 == 0 else 'Odd'
```

```text
'Odd'
```


## Code cell 112

```python
# Example 2: Return True if a given element is in a list and False if not

nums = [1,2,3,4,5,6]

True if 3 in nums else False
```

```text
True
```


## Code cell 113

```python
even_nums = [2,4,6,8,10]

for num in even_nums:
  print(num)
```

```text
2
4
6
8
10
```


## Code cell 114

```python
week_days = ['Mon', 'Tue', 'Wed', 'Thur','Fri']

for day in week_days:
  print(day)
```

```text
Mon
Tue
Wed
Thur
Fri
```


## Code cell 115

```python
sentence = "It's been a long time learning Python. I am revisiting the basics!!"

for letter in sentence:
  print(letter)
```

```text
I
t
'
s
 
b
e
e
n
 
a
 
l
o
n
g
 
t
i
m
e
 
l
e
a
r
n
i
n
g
 
P
y
t
h
o
n
.
 
I
 
a
m
 
r
e
v
i
s
i
t
i
n
g
 
t
h
e
 
b
a
s
i
c
s
!
!
```


## Code cell 116

```python
sentence = "It's been a long time learning Python. I am revisiting the basics!!"

# split is a string method to split the words making the string

for letter in sentence.split():
  print(letter)
```

```text
It's
been
a
long
time
learning
Python.
I
am
revisiting
the
basics!!
```


## Code cell 117

```python
# For loop in dictionary

countries_code = { "United States": 1,
                 "India": 91,
                 "Germany": 49,
                 "China": 86,
                 "Rwanda":250
            }

for country in countries_code:
  print(country)
```

```text
United States
India
Germany
China
Rwanda
```


## Code cell 118

```python
for code in countries_code.values():
  print(code)
```

```text
1
91
49
86
250
```


## Code cell 119

```python
for number in range(10):
  print(number)
```

```text
0
1
2
3
4
5
6
7
8
9
```


## Code cell 120

```python
for number in range(10, 20):
  print(number)
```

```text
10
11
12
13
14
15
16
17
18
19
```


## Code cell 121

```python
letters = []

for letter in 'MachineLearning':
  letters.append(letter)

letters
```

```text
['M', 'a', 'c', 'h', 'i', 'n', 'e', 'L', 'e', 'a', 'r', 'n', 'i', 'n', 'g']
```


## Code cell 122

```python
letters = [letter for letter in 'MachineLearning']

letters
```

```text
['M', 'a', 'c', 'h', 'i', 'n', 'e', 'L', 'e', 'a', 'r', 'n', 'i', 'n', 'g']
```


## Code cell 123

```python
a = 10
while a < 20:
    print('a is: {}'.format(a))
    a = a + 1
```

```text
a is: 10
a is: 11
a is: 12
a is: 13
a is: 14
a is: 15
a is: 16
a is: 17
a is: 18
a is: 19
```


## Code cell 124

```python
# Function to add two numbers and return a sum

def add_nums(a,b):

  """
  Function to add two numbers given as inputs
  It will return a sum of these two numbers
  """

  sum = a+b

  return sum
```


## Code cell 125

```python
add_nums(2,4)
```

```text
6
```


## Code cell 126

```python
add_nums(4,5)
```

```text
9
```


## Code cell 127

```python
# Displaying the doc string noted early

print(add_nums.__doc__)
```

```text

  Function to add two numbers given as inputs
  It will return a sum of these two numbers
```


## Code cell 128

```python
def activity(name_1, name_2):

  print("{} and {} are playing basketball!".format(name_1, name_2))
```


## Code cell 129

```python
activity("Chris", "Francois")
```

```text
Chris and Francois are playing basketball!
```


## Code cell 130

```python
activity("Kennedy", "Kleber")
```

```text
Kennedy and Kleber are playing basketball!
```


## Code cell 131

```python
## Sum of two numbers

def add_nums(a,b):

  sum = a+b

  return sum

add_nums(1,3)
```

```text
4
```


## Code cell 132

```python
sum_of_two_nums = lambda c,d: c + d

sum_of_two_nums(4,5)
```

```text
9
```


## Code cell 133

```python
# using len() to count the length of the string

message = 'Do not give up!'
len(message)
```

```text
15
```


## Code cell 134

```python
odd_numbers = [1,3,5,7]
len(odd_numbers)
```

```text
4
```


## Code cell 135

```python
# Using max() to find the maximum number in a list

odd_numbers = [1,3,5,7]
max(odd_numbers)
```

```text
7
```


## Code cell 136

```python
# Using min() to find the minimum number in a list

min(odd_numbers)
```

```text
1
```


## Code cell 137

```python
# Sorting the list with sorted()

odd_numbers = [9,7,3,5,11,13,15,1]

sorted(odd_numbers)
```

```text
[1, 3, 5, 7, 9, 11, 13, 15]
```


## Code cell 138

```python
def cubic(number):
  return number ** 3
```


## Code cell 139

```python
num_list = [0,1,2,3,4]
```


## Code cell 140

```python
# Applying `map` to the num_list to just return the list where each element is cubed...(xxx3)

list(map(cubic, num_list))
```

```text
[0, 1, 8, 27, 64]
```


## Code cell 141

```python
def odd_check(number):

  return number % 2 != 0

# != is not equal to operation
```


## Code cell 142

```python
num_list = [1,2,4,5,6,7,8,9,10,11]

list(filter(odd_check, num_list))
```

```text
[1, 5, 7, 9, 11]
```


## Code cell 143

```python
# Given a list of numbers, can you make a new list of even numbers from the list nums?
# Even numbers are numbers divisible by 2, and they give the remainder of 0

nums = range(1,20)
even_nums = []


# A traditional way to do it is:

for num in nums:
  if num % 2 == 0:
    even_nums.append(num)

print(even_nums)
```

```text
[2, 4, 6, 8, 10, 12, 14, 16, 18]
```


## Code cell 144

```python
even_nums = [num for num in nums if num % 2 == 0]
print(even_nums)
```

```text
[2, 4, 6, 8, 10, 12, 14, 16, 18]
```


## Code cell 145

```python
days = ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday']
day_T = []

# Make a list of days that start with `T`

for day in days:
  if day[0] == 'T':
    day_T.append(day)

print(day_T)
```

```text
['Tuesday', 'Thursday']
```


## Code cell 146

```python
day_T = [day for day in days if day[0] == 'T']
print(day_T)
```

```text
['Tuesday', 'Thursday']
```


## Code cell 147

```python
seasons = ['Spring', 'Summer', 'Fall', 'Winter']

list(enumerate(seasons))
```

```text
[(0, 'Spring'), (1, 'Summer'), (2, 'Fall'), (3, 'Winter')]
```


## Code cell 148

```python
list(enumerate(seasons, start=1))
```

```text
[(1, 'Spring'), (2, 'Summer'), (3, 'Fall'), (4, 'Winter')]
```


## Code cell 149

```python
class_names = ['Rock', 'Paper', 'Scissor']

for index, class_name in enumerate(class_names, start=0):
  print(index,'-',class_name)
```

```text
0 - Rock
1 - Paper
2 - Scissor
```


## Code cell 150

```python
name = ['Jessy', 'Joe', 'Jeannette']
role = ['ML Engineer', 'Web Developer', 'Data Engineer']

zipped_name_role = zip(name, role)
zipped_name_role
```

```text
<zip at 0x10a4e1580>
```


## Code cell 151

```python
list(zipped_name_role)
```

```text
[('Jessy', 'ML Engineer'),
 ('Joe', 'Web Developer'),
 ('Jeannette', 'Data Engineer')]
```
