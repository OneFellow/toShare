# main file
import test002

play = True


while play == True:

	print "Do you want to add a number?"
	tf = raw_input("y/n: ")
	
	if tf == "y":
		print "How much do you want to add by?"
		y = int(raw_input("> "))
		x.add_Num(y)
		
	else:
		print "Terminating program...\n\n"
		play = False
		
------------------------------------------
# This is test002
		
class arithmetic(object):
	def __init__(self):
		self.number = 00
		
	def add_Num(self, num):
		self.number += num
		return self.number
	
x = arithmetic()

