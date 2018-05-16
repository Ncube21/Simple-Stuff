# Simple-Stuff

#First, swapping of numbers in just one line of code.

a = 1
b = 2 
c = 4
d = 5
print (a,b,c,d) #before (1,2,4,5)
d,c,b,a = a,b,c,d
print (a,b,c,d) #after (5,4,2,1)



#to convert a list of integers to an list of strings?

l = [1,2,3,4]
map( l,str )
print (''.join(l)) #1234
