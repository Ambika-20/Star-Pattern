# Star-Pattern
#To print Stars in a pattern
n=int(input("Enter number of rows to be printed:"))
for i in range(1,n+1):
    for j in range(1,i+1):
        print("*", end=" ")
    print()
