# list.python

list =["item1","item2","item3"]

print(list[0]) #op: item1
print(list[1]) #op: item3
print(list[2]) #op: item2

#list can hold variable element of different datatype
list2 =[1,"string",True,3.14]
#you can also make list within list
list3 =[1,"string",True,3.14,[5,6,7]]
print(list3[4][0])

list3.pop() #pop() is used to remove last element of the list
print(list3) #op:[1, 'string', True, 3.14]

# you can also remove elements of list by using their index number
list3.pop(0)
print(list3) # op:['string', True, 3.14]

#to add something to list ,append key word is used
list3.append("example")
print(list3) # op:['string', True, 3.14, 'example']

list3.remove("example")
print(list3) #op:['string', True, 3.14]

''' the difference between remove and pop() is pop uses index number of element on the list to delete but remove uses value of element on the list'''


list3.insert(1,"string2")
print(list3) #op:['string', True, 3.14]
''' insert() is helps to add an element wherever we wish to place in accordance to their index number'''

#list3.clear()
#print(list3) #op:[]
#clear() delete all the elements of the list

list3[0]=2 #to replace element of the list 
print(list3) #op:[2, 'string2', True, 3.14]
 


A=[1,2,3,4,5,]
print(A[0:3]) #op:[1, 2, 3]

''' slicing of element can be done by using of index position'''
B=[33,54,88,1]
print(sorted(B)) #op:[1, 33, 54, 88]
#sorted is used to put elements in ascending order
