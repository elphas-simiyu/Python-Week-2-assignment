The code contains solutions to the question below

Create an empty list called my_list.
Append the following elements to my_list: 10, 20, 30, 40.
Insert the value 15 at the second position in the list.
Extend my_list with another list: [50, 60, 70].
Remove the last element from my_list.
Sort my_list in ascending order.
Find and print the index of the value 30 in my_list.

And this is the python program for the question

# Question 1: Create an empty list
my_list = []

# Questin 2: Append the elements 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Question 3: Insert the value 15 at the second position
my_list.insert(1, 15)

# Question 4: Extend my_list with [50, 60, 70]
my_list.extend([50, 60, 70])

# Question 5: Remove the last element
my_list.pop()

# Question 6: Sort the list in ascending order
my_list.sort()

# Question 7: Find and print the index of the value 30
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
