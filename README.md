# Tokyo-Ghoul
Tokyo Ghoul in Python


# ghoul
# import our modules
import time
from colorama import Fore, Back
from colorama import init
init()
# print phrase from anime
# and add some color here
print(Fore.WHITE)
time.sleep(1.550)
print("I'm...")
time.sleep(1.800)
# and here
print(Fore.RED)
print("Ghoul...")
time.sleep(1.000)

# create function

def ghoul():
	# variable from which we will calculate 7
	a = 1000
	# cycle
	while a > 0:
		a = a - 7
		b = a + 7 
		# formatting and print
		# aaand here some color
		time.sleep(0.050)
		print(Fore.WHITE)
		print(Back.RED)
		print(f"{b}-7={a}") 
# start out function
ghoul()

