# system-integration-and-architechture-2
print('Hello SPUS!')




#Exercise 3 odd or even
#create a python program that determines if the number is odd or eve based on the user input.

user_input = input ( "enter number? ")

try
number = int (user_input)
if number 2 % == 0:
print ( f"{number} is an even number.")

else:
print(f"{number} is an odd number")
exept ValueError:
print("You did not enter a number.")



#exercise 4 for loops
#crate a python program that displays all even numbers from 1 to 100 using for loops

for i in range(0, 101): #loops
  if i%2==0: #checks if even
      print(i) #prints the even number
