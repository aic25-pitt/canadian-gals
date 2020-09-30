The program asks the user for their name, then stores it in a name variable.

Then, it asks the user for their birthday, and stores the month and day in a month and day variable. 

It then compares the month and day variables to determine the person's zodiac sign. 

It prints "[user's name], you are a [zodiac sign].”

Here are a few snippits of how it works:

```python
name = input(“What is your name?”)
month = int(input(“What month were you born in? (Number)”))
day = int(input(“What day of the month were you born on?”))
```

```python
if(month == 6):
if(day<=20):
	sign = “Gemini”
else:
	sign = “Cancer”
```


Here is an example of what it should look like when it runs:

"What is your name?"	Bob
"What month were you born in? (Number)"	3
"What day of the month were you born on?"	22

"Bob, you are a Aries"



