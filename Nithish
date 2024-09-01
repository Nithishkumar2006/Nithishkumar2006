import random

import string

def generate_password(length=12):

if length < 4:

raise ValueError("Password length should be at least 4 characters to include

#Define character sets

uppercase string.ascii_uppercase

lowercase = string.ascii_lowercase

digits string.digits

special_characters = string.punctuation.

#Ensure the password has at least one of each type of character

password=[

random.choice(uppercase),

random.choice(lowercase).

random.choice(digits), random.choice(special_characters)

9

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

20

1

21

22

23

24

25

26

27

28

29

30

31

32

33

34

password generate_password(password_length)

#Fill the rest of the password length with a random selection of all character all_characters uppercase lowercase digits special_characters password random.choices(all_characters, k=length-4)

#Shuffle the password list to ensure randomness

random.shuffle(password)

#Join the list into a string and return

return.join(password)

#Example usage

password_length = 16

35 printf Generated password: (password)")
