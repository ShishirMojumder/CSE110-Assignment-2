# CSE110 Assignment 2 
# Task01
counter = 18 

while counter <= 63 :
    if (counter%2!=0):
        print(counter*-1,end=",")
    else:
        print(counter,end=",")
    counter = counter + 9
