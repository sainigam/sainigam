
myList = []
 

n = int(input("How many element in list  "))
 
for i in range(n):
    storeElement = input ("Enter the string :- ")
    myList.append (storeElement)
 

    
print("How far is "+str(myList[0])+ " from " +str(myList[1]))
print("How far is "+str(myList[1])+ " from " +str(myList[0]))

print("How is the weather in " +str(myList[0]))
print("How is the weather in " +str(myList[1]))
