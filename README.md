# Udemy_Phyton_ZTM 
Regarding annotation the course

Contents
--------
**Exercise:** **[`Exercise22`](#exercise22)__,__[`None`](#none)__,__**

**Annotation:** **[`Content21`](#content21)__,__[`Content26`](#content26)__,__[`Content30`](#content30)__,__[`Content31`](#content31)__,__[`Content32`](#content32)__,__[`Content34`](#content34)__,__[`Content35`](#content35)__,__[`Content36`](#content36)__,__[`Content40`](#content40)__,__**

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
```
```python
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
```
```python
# example_02  adding "\"
weather = 'It\'s king of sunny'
print(weather)
#return It's king of sunny
```
```python
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
```
```python
# formatted string example_02 add "f" begin the sentence
name = 'Jonnhy'
age = 45

print(f'Hi {name}. You are {age} years old')
'''
return
Hi Jonnhy. You are 45 years old
'''
```
```python
# format string example_03 add "format"
name = 'Johnny'
age = 40

print('Hi {}. You are {} years old'.format('Johnny','40'))
'''
return
Hi Johnny. You are 40 years old.
'''
```
Content32
--------
**Ummutability, String reverse**

```python
selfish = 'example'
          #0123456

'''
Para sequencia direita para esquerda
[0] -> e
[1] -> x
[2] -> a
[3] -> m
[4] -> p
[5] -> l
[6] -> e

Para sequencia esquerda para direita (reverso)[-1]
selfish = example
          7654321      
[1] -> e
[2] -> l
[3] -> p

Para sequencia esquerda para direita (reverso) [-2]
selfish = example
          7654321      
[2] -> l
[3] -> p
[4] -> m

'''
```
```python

selfish = 'example'
          #0123456

# [start:stop:stepover]
print(selfish[:5])
# return : examp
```
```Pyhton
selfish = 'example'
          #0123456

# [start:stop:stepover]
print(selfish[::1])
# return : example
```
```python
selfish = 'example'
          #0123456

# [start:stop:stepover]
print(selfish[::-1])
# return : elpmaxe
```
```python
selfish = 'example'
          #0123456

# [start:stop:stepover]
print(selfish[::-1])
print(selfish[::-2])
print(selfish[::-3])
print(selfish[::-4])
print(selfish[::1])
print(selfish[::2])
print(selfish[::3])
print(selfish[::4])

'''
print(selfish[::-1]) ->  elpmaxe
print(selfish[::-2]) -> epae
print(selfish[::-3]) -> eme
print(selfish[::-4]) -> ea
print(selfish[::1]) -> example
print(selfish[::2]) -> eape
print(selfish[::3]) -> eme
print(selfish[::4]) -> ep
'''
```
Content34
--------
**Construction function, lenght of string**

```python
# constrution functions
print(len('amazing'))
#          1234567
'''
Note that lengt of string start with number "1"
return : 7
'''
```
Content35
--------
**Simple concectp Booleans**

```python
name = "example"

value_bool = False
value_biol = True

print(bool(1))
print(bool(0))
'''
return
print(bool(1)) -> True
print(bool(0)) -> False

'''
```
Content36
--------
**Type Convert**

```python
birth_year = input('What year are you born ?')
age = 2019 - int(birth_year)

print(f'You age is: {age}')
'''
return
input : 1976
You age is : 43
'''
'''
```
Content40
--------
**List Slincing**

```python
# list slicing
amazon_cart = ['notebooks','sunglasse','toys','grapes']
amazon_cart[0] = 'laptop'
new_cart = amazon_cart [:]
new_cart[0] = 'gum'
print(new_cart)
print(amazon_cart)
'''
return
['gum', 'sunglasse', 'toys', 'grapes']
['laptop', 'sunglasse', 'toys', 'grapes']

# This is idea of copying vc modifying
'''
```
