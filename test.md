done = False

def stop():
	done = True
	
while done == False:
	print "Do you want to quit?"
	ans = raw_input("y/n: ")
	if ans == "y":
		stop()
