# Udemy_Phyton_ZTM 
Regarding annotation the course

Contents
--------
**Exercise:** **[`Exercise22`](#exercise22)__,__[`None`](#none)__,__**

**Annotation:** **[`Content21`](#content21)__,__[`Content26`](#content26)__,__[`Content30`](#content30)__,__**

Exercise22
--------
**Annotation regarding exercise, topics most relevant.**

```python
# # Guess the output of each answer before you click RUN
# Try to write down your answer before and see how you do... keep it mind I made it a little tricky for you :)

print((5 + 4) * 10 / 2)

print(((5 + 4) * 10) / 2)

print((5 + 4) * (10 / 2))

print(5 + (4 * 10) / 2)

print(5 + 4 * 10 // 2)

```

Content21
--------
**Sequence priority - math**

```python
# operator precedence
print((20 - 3) + 2 ** 2)

# ( )
# **
# * /
# + -
```

Content26
--------
**Some representation with arguments**

```python
# argumented assignment operator
# example_01
some_value = 5
some_value = some_value * 2
print(some_value)
# retun 10

# example_02
some_value = 5
some_value *= 3
print(some_value)
# return 15

```
Content30
--------
**Regarding scape sentence**

```python
# example_01 without "\"
weather = 'It's king of sunny'
print(weather)
"""
ERROR bellow
weather = 'It's king of sunny'
                  ^
SyntaxError: invalid syntax
"""

# example_02  adding "\"
weather = 'It\'s king of sunny'
print(weather)
#return It's king of sunny

# example_03 put word between "" in middle of the sentence
weather = "It's \"king of\" sunny"
print(weather)
# return : It's "king of" sunny
```
Content31
--------
**Regarding formatted String**

```python
# formatted string example_01
name = 'Jonnhy'
age = 45
print( "Hi " +name+ "! You have " + str(age) + " years old.")
'''
return
Hi Jonnhy ! You have 45 years old
'''
# formatted string example_02 add "f" begin the sentence
name = 'Jonnhy'
age = 45

print(f'Hi {name}. You are {age} years old')
'''
return
Hi Jonnhy. You are 45 years old
'''

```
