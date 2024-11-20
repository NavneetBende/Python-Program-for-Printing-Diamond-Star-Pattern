Print Diamond Star Pattern
In this Python Program, we will be discussing about how to write a program to print Diamond Star Pattern. In this pattern, there are n rows with i numbers of time of iterations through all the rows. In columns, num-i-1 numbers for printing Spaces and i*2+1 numbers for printing stars. Run another loop with i(Starts from 1) numbers of time of iterations through all the rows. In columns, i numbers for printing Spaces and (num-i)*2-1 numbers for printing stars. So, User have to enter a single value, that will be determine as a number of rows of the pattern. With the help of “Two Different Different Nested For Loop” , we will print the Diamond Star Pattern.

Python Program for Printing Diamond Star Pattern
Working:
Step 1. Start

Step 2. Take number of rows as input from the user and stored it into num.

Step 3. Run a loop ‘i’ number of times to iterate through all the rows which is Starting from i=0 to num. 

Step 4. Run a nested loop inside the main loop for printing spaces which is starting from j=0 to num-i-1.

Step 5. Run a nested loop inside the main loop for printing stars which is starting from j=0 to i*2+1.

Step 6. Move to the next line by printing a new line using print() function.

Step 7. Run a loop ‘i’ number of times to iterate through all the rows which is Starting from i=1 to num. 

Step 8. Run a nested loop inside the main loop for printing spaces which is starting from j=0 to i.

Step 9. Run a nested loop inside the main loop for printing stars which is starting from j=0 to (num-i)*2-1.

Stop 10. Move to the next line by printing a new line using print() function.

Step 11. Stop

Python Program:
num = int(input("Enter the Number: "))

for i in range(0, num):
    for j in range(0, num-i-1):
        print(" ",end="")
    for j in range(0, i*2+1):
        print("*", end="")
    print()

for i in range(1, num):
    for j in range(0, i):
        print(" ",end="")
    for j in range(0, (num-i)*2-1):
        print("*", end="")
    print()

