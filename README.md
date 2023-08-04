import time
import sys

def write(str, eol = "\n"):
    for char in str:
        time.sleep(.1)
        sys.stdout.write(char)
        sys.stdout.flush()
    sys.stdout.write(eol)
    sys.stdout.flush()

write("Welcome to the Number Guessing Game")
write("Can you guess the number?")
