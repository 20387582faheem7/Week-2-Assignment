# Week-2-Assignment
my_list = []

my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

my_list.insert(1, 15)

my_list.extend([50, 60, 70])

if my_list:
    my_list.pop()

my_list.sort()

if 30 in my_list:
    index_30 = my_list.index(30)
    print("Index of 30:", index_30)
else:
    print("30 is not in the list")

print("Final List:", my_list)


