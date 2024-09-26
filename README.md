# PsuedoCodeForClass

#Guess the Number Game
 
Display Select a random number between x and x
Ask user to enter a number between x and x
While the guess is incorrect
    if it's too high then print "Try lower..."
    if it's too low then print "Try higher..."
    request another guess from the user
While guess is correct
  print "Conrratulations! You guessed right!"

#Find the Spot

Display "Welcome to the Warehouse Navigation System!"
Set current_x and current_y to the customer's current position
Set target_x and target_y to the target location

While current_x is not equal to target_x OR current_y is not equal to target_y:

If current_x < than target_x 
Display "Move East"
Increase current_x by 1

IF current_x is > than target_x 
Display "Move West"
Decrease current_x by 1

If current_y is < than target_y 
Display "Move North"
Increase current_y by 1

If current_y is > than target_y
Display "Move South"
Decrease current_y by 1

Display "Current Position: (current_x, current_y)"

When current_x equals target_x AND current_y equals target_y:
Display "You have reached your destination!"

#Product Package Counter

Initialize a counter current_count to 2 (since each package scanned contains 2 products).
Set the maximum limit to 50 for the number of product packages.
While current_count is less than or equal to 50:
Print current_count.
Increment current_count by 2.
End While loop when current_count exceeds 50.
