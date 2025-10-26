
# coding: utf-8

# In[1]:



n = input('Enter name: ')

for i in n:
    if i in 'aeiouAEIOU':
        continue
    else:
        print(i)


# In[2]:


total=0
while True:
    num=int(input("enter a number"))
    total=total+num
    if total>300:
        print("sum exceeded 300.total sum is:",total)
        break


# In[ ]:


while True:
    s=input("enter string")
    if s=="bon":
        print ("voyage")
        break


# In[ ]:


address = input("Enter your door number and street")
numbers = ""
for i in address:
    if '0' <= i <= '9':
        numbers += i
print("Numbers in the address:", numbers)


# In[ ]:


a = input("Enter first element: ")
b = input("Enter second element: ")
c = input("Enter third element: ")
d = input("Enter fourth element: ")
e = input("Enter fifth element: ")
list = [a, b, c, d, e]

name = input("Enter name: ")
list[2] = name
list[4] = name
print("Updated list:", list)


# In[ ]:


list_input = input("Enter elements : ")
list = list_input.split()  # Convert string to list
i = int(input("Enter index: "))
e = input("Enter new element: ")
if i >= 0 and i <= len(list):
    list.insert(i, e)
else:
    print("Invalid index, element will not be appended.")
    list.append(e)

print("Updated list:", list)

