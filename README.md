library = {1:"toy", 2:"box", 3:"name", 4:example()}

class example(object):
	stuff = "nothing"
		
def makeProxy(x):
	proxy = library[x]
	return proxy
	
for i in library:
	print makeProxy(i)
	print
