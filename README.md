# PYTHON_DATA_STRUCTURES

# Python fundamentals: practicing data structures including lists, dictionaries, sets, and tuples.

# List
# Q1. Create a list of 5 random numbers and print the list.

import random

r_num= [random.randint(1, 100) for _ in range(5)]

print(r_num,type(r_num))

![lq1](https://github.com/user-attachments/assets/a3d2fcdd-fac3-4dcf-8866-93bbaa5221f5)

# Q2. Insert 3 new values to the list and print the updated list.

import random

r_num= [random.randint(1, 100) for _ in range(5)]

print("Original List",r_num)

new_values = [random.randint(1, 100) for _ in range(3)]

r_num.extend(new_values)

print("Updated List",r_num)

![lq2](https://github.com/user-attachments/assets/57b5241d-bbe6-4388-8bb7-2b53650f405a)

# Q3. Try to use a for loop to print each element in the list.

import random

r_num= [random.randint(1, 100) for _ in range(5)]

print("Original List",r_num)

new_values = [random.randint(1, 100) for _ in range(3)]

r_num.extend(new_values)

print("Updated List",r_num)

for i in r_num:

  print(i)

![lq3](https://github.com/user-attachments/assets/07b7c98f-595c-455e-91df-8f27a537f61c)

# Dictionary

# Q1. Create a dictionary with keys 'name', 'age', and 'address' and values 'John', 25, and 'New York' respectively.

user = {
    'name': 'John',
    'age': 25,
    'address': 'New York'
}

print(user)

![dq1](https://github.com/user-attachments/assets/7c068ca9-3c47-44de-b8b9-8478193ff819)

# Q2. Add a new key-value pair to the dictionary created in Q1 with key 'phone' and value '1234567890'.

user['phone'] = '1234567890'

print(user)

![dq2](https://github.com/user-attachments/assets/7bcf6f95-69df-482d-9a6d-41e792a90ef4)

# Set

# Q1.Create a set with values 1, 2, 3, 4, and 5.

set = {1, 2, 3, 4, 5}

print("SET=",set,"\n","TYPE=",type(set))

![sq1](https://github.com/user-attachments/assets/b4dcc7d6-00ad-462a-bb7b-06100f9c1b9e)

# Q2.Add the value 6 to the set created in Q1.

set.add(6)

print(set)

![sq2](https://github.com/user-attachments/assets/5bdaaea5-7dfc-4402-9ae8-71a2cfe3ed65)

# Q3.Remove the value 3 from the set created in Q1.

set.remove(3)

print(set)

![sq3](https://github.com/user-attachments/assets/a83f8ce1-5e5f-4e23-8e70-e6c2c62f1ecc)

# Tuple

# Q1. Create a tuple with values 1, 2, 3, and 4

tuple = (1, 2, 3, 4)

print("TUPLE=",tuple,"\n","TYPE=",type(tuple))

![tq1](https://github.com/user-attachments/assets/7e1e3ca1-c205-4f26-a62e-9dcdbdf1063c)

# Q2. Print the length of the tuple created in Q1.

print("LENGTH=",len(tuple))

![tq2](https://github.com/user-attachments/assets/3e126efb-f2db-4776-8352-ecbf0b6c689f)




