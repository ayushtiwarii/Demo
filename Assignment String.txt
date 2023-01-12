a="Hello"
print(a)

# slicing

b = "Slicing, code"
print(b[2:5])

b = "Slicing, code"
print(b[2:])

#Upper Case

a = "ayush tiwari"
print(a.upper())

# Remove white space

a = " Removing White Space "
print(a.strip()) 

# Replace string

a = "Ayush, Tiwari"
print(a.replace("A", "T"))

# Split String

a = "Spliting, String"
print(a.split(","))

# Concatenate String

a = "Ayush"
b = "Tiwari"
c = a + b
print(c)

# String Format

age = 22
txt = "My name is Ayush, and I am {}"
print(txt.format(age))

# count method

txt = "Python is a widely used language and Python helps us in automation"

x = txt.count("Python")

print(x)

# Encode method

txt = "My name is Ayush"
x = txt.encode()
print(x)

# Find Method

txt = "Welcome to Python Learning."
x = txt.find("Python")
print(x)

#Join Method
myTuple = ("Ayush", "Ishaan", "Dev")
x = "#".join(myTuple)
print(x)

#Replace
txt = "I like bananas"
x = txt.replace("bananas", "apples")
print(x)

#StartsWith
txt = "Welcome to python learning"
x = txt.startswith("Welcome")
print(x)

# Access List Items
thislist = ["apple", "banana", "cherry"]
print(thislist[1])

#Change Item Value

thislist = ["apple", "banana", "cherry"]
thislist[1] = "watermelon"
print(thislist)

thislist = ["apple", "banana", "cherry"]
thislist[1:2] = ["orange", "watermelon"]
print(thislist)

#Insert item in List

thislist = ["apple", "banana", "cherry"]
thislist.insert(1, "orange")
print(thislist)

#Loop in List

thislist = ["apple", "banana", "cherry"]
for i in range(len(thislist)):
  print(thislist[i])

#Sort List

thislist = [100, 50, 65, 82, 23]
thislist.sort()
print(thislist)

#Join Two List
list1 = ["a", "b", "c"]
list2 = [1, 2, 3]

list3 = list1 + list2
print(list3)

list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

for x in list2:
  list1.append(x)

print(list1)

#Join Two Sets

set1 = {"a", "b" , "c"}
set2 = {1, 2, 3}

set3 = set1.union(set2)
print(set3)

#Difference between two set

x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}

z = x.difference(y)

print(z)

#Union between two set

x = {"apple", "banana", "cherry"}
y = {"google", "microsoft", "apple"}

z = x.union(y)

print(z)