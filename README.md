#  SelectionSort.py
# Assending order of list with user input by min()

list=[]
a=int(input("Enter the number of list:"))

for i in range(a):
    list.append(int(input("Enter the number:")))

print("Original List :",list)

for i in range(len(list)):
    min_val=min(list[i:])
    min_ind=list.index(min_val)
    list[i],list[min_ind]=list[min_ind],list[i]

print("Sorted List :",list)

    
    
