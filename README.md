# fibonacci
# it is the series of the numbers that follow the sequence as 0 , 1 , 1 , 2 , 3 , 5 , 8 , 13 , 21 , 24.....
# it is a recurrence realtion
def fibo(n):
n = int(input("number of terms in the series :"))
n1 , n2 = 0 , 1
count = 1
if n <= 0 :
 print ("please neter a positive integer)
elif n == 1: 
 print ("fibonacci sequence upto n terms ",n,":")
 print(n1)
else:
 print("fibonacci sequence:")
 while count < n:
  print n1
  nth = n1 + n2
  n1 = n2
  n2 = nth
  count += 1
 
