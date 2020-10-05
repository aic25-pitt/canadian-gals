The program asks the user for their name, then stores it in a name variable.

Then, it asks the user for their birthday, and stores the month and day in a month and day variable. 

It then compares the month and day variables to determine the person's zodiac sign. 

It prints "[user's name], you are a [zodiac sign].”

Here are a few snippits of how it works:

```python
name = input("What is your name?")
month = int(input("What month were you born in? (Number)"))
day = int(input("What day of the month were you born on?"))
```

```python
if(month == 6):
	if(day<=20):
		sign = "Gemini"
	else:
		sign = "Cancer"
```


Here is an example of what it should look like when it runs:

"What is your name?"	Bob
"What month were you born in? (Number)"	3
"What day of the month were you born on?"	22

"Bob, you are a Aries"


HOW TO CONTRIBUTE

We chose this code of conduct because it included all the rules we expect a user to follow. It also states what behavior is acceptable and unacceptable, so that all users, no matter their background, feel welcome to use the program. If anything goes wrong, people will know how they should react, and what steps to take in response. 


USE AND INSTALLATION

We chose this license because it includes who can use the software and how they can use it.  We wanted it to be open-source, and we wanted people to be able to alter the code for themselves if they wanted to. 

To install the code, first open the repository on github. Then, copy the repository’s URL from the green dropdown box named “Code”. Type the following command into your terminal: git clone <URL>
Next, type this command to view all repositories on your computer: ls
Then, use this command to open a certain repository: cd <repo name>
Then use ls again to view all the files in that repo.
To open any file, use the command: cat <file name>
To edit any file, use the command vim <file name>
Then, to save the edited file and exit out of vim, press the esc key and type :wq
To ensure that your edited file saved, use the command ls again, and then cat <file name>

