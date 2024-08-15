# Ask-out
Date Purposal
import time

def print_delayed_message(message, delay=1):
    """Prints a message with a delay to build suspense."""
    for char in message:
        print(char, end='', flush=True)
        time.sleep(delay)
    print()

def date_proposal():
    print_delayed_message("Hi [Crush's Name],")
    time.sleep(1)
    
    print_delayed_message("I've been thinking a lot about how much fun it would be to spend some time together.")
    time.sleep(2)
    
    print_delayed_message("I was wondering...")
    time.sleep(1)
    
    print_delayed_message("Would you like to go on a date with me?")
    time.sleep(2)
    
    print_delayed_message("I've been looking forward to getting to know you better.")
    time.sleep(1)
    
    print_delayed_message("How about [Proposed Date/Activity]?")
    time.sleep(2)
    
    print_delayed_message("I hope you say yes!")
    time.sleep(1)
    
    print_delayed_message("Looking forward to hearing from you!")
    
if __name__ == "__main__":
    date_proposal()
