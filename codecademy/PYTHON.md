# codecademy_PYTHON

## TIP CALCULATOR

~~~python
# Assign the variable total on line 8!

meal = 44.50
tax = 6.75 / 100
tip = 15.0 / 100

meal = meal + meal * tax
total = meal + meal * tip


print("%.2f" % total)
~~~



---

## STRINGS AND CONSOLE OUTPUT

### string indexing

```python
#+---+---+---+---+---+---+
#| P | Y | T | H | O | N |
#+---+---+---+---+---+---+
#  0   1   2   3   4   5
    
"python"[3] == H

var1 = 'Hello World!'
var2 = "Python Programming"

print "var1[0]: ", var1[0] # var1[0]:  H
print "var2[1:5]: ", var2[1:4+1] # var2[1:5]:  ytho
print "var2[:6]: ", va1[:5+1] # va1[:6]: python
```

### back slash

~~~python
'This isn\'t flying, this is falling with style!'
'This isn't flying, this is falling with style!'
# ' or " 앞 백슬래쉬( \ )는 string처리를 무시한다 
~~~

### string method

~~~python
len() # length
str() # string

"string".lower() # lower letter 
"string".upper() # upper letter 
# Methods that use dot notation only work with strings
# 변수 자체를 바꾸는것이 아니다.
~~~

### Explicit String Conversion

~~~python
print "The value of pi is around " + str(3.14)
# string 은 string 끼리만 더할 수 있다.
~~~

### String Formatting with %

~~~python
name = raw_input("What is your name? ")
quest = raw_input("What is your quest? ")
color = raw_input("What is your favorite color? ")

print "Ah, so your name is %s, your quest is %s, " \
"and your favorite color is %s." % (name, quest, color)
~~~







