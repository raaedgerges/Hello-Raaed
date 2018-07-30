# Hello-Raaed
Test
#Hello People This is a password generator script 
import string
from random import *
characters = string.ascii_letters + string.punctuation  + string.digits
password =  "".join(choice(characters) for x in range(randrange(2, 10)))
print (password)
