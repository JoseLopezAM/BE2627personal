import time 
#mission status light controller 

GREEN = "\033[92m"
YELLOW = "\033[93m"
RED = "\033[91m"
RESET = "\033[0m"

def show_light(color, message):
    """Display the current light color and statues."""
    print("\n" + "=" * 35)

    if color ==