# Python-Average-Calculator

count = int(input("Enter the count of numbers: ")) 
i = 0 
sum = 0 
for i in range(count): 
 x = int(input("Enter an integer: ")) 
 sum = sum + x 
avg = sum/count 
print(" The average is: ", avg) 

Output:
Enter the count of numbers: 4
Enter an integer: 12
Enter an integer: 23
Enter an integer: 34
Enter an integer: 56
 The average is:  31.25
