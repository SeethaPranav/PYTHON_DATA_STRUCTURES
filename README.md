# PYTHON_DATA_STRUCTURES
Python fundamentals: practicing data structures including lists, dictionaries, sets, and tuples.
List
Q1. Create a list of 5 random numbers and print the list.
import random
r_num= [random.randint(1, 100) for _ in range(5)]
print(r_num,type(r_num))


Q2. Insert 3 new values to the list and print the updated list.
import random
r_num= [random.randint(1, 100) for _ in range(5)]
print("Original List",r_num)
new_values = [random.randint(1, 100) for _ in range(3)]
r_num.extend(new_values)
print("Updated List",r_num)

Q3. Try to use a for loop to print each element in the list.
import random
r_num= [random.randint(1, 100) for _ in range(5)]
print("Original List",r_num)
new_values = [random.randint(1, 100) for _ in range(3)]
r_num.extend(new_values)
print("Updated List",r_num)
for i in r_num:
    print(i)

Dictionary
Q1. Create a dictionary with keys 'name', 'age', and 'address' and values 'John', 25, and 'New York' respectively.

user = {
    'name': 'John',
    'age': 25,
    'address': 'New York'
}
print(user)

Q2. Add a new key-value pair to the dictionary created in Q1 with key 'phone' and value '1234567890'.
user['phone'] = '1234567890'
print(user)

Set
Q1.Create a set with values 1, 2, 3, 4, and 5.
set = {1, 2, 3, 4, 5}
print("SET=",set,"\n","TYPE=",type(set))

Q2.Add the value 6 to the set created in Q1.
set.add(6)
print(set)

Q3.Remove the value 3 from the set created in Q1.
set.remove(3)
print(set)

Tuple
Q1. Create a tuple with values 1, 2, 3, and 4
tuple = (1, 2, 3, 4)
print("TUPLE=",tuple,"\n","TYPE=",type(tuple))


Q2. Print the length of the tuple created in Q1.
print("LENGTH=",len(tuple))

