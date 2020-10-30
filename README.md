print("Welcome to star pattern printer")
B=int(input("Enter 0 for simple pattern and any number for reverse pattern\n")) 
n=int(input("Enter the number of rows\n"))
if B==False:
	i=0
	while i<n:
		i=i+1
		print((i)*"*") 
else:
		i=0
		while i<n:
			i=i+1
			print((n+1-i)*"*") 
print("Thanks for using star pattern printer") 
