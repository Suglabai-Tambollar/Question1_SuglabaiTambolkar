# Question1_SuglabaiTambolkar
def printDivisors(n):
  i=1
  while i<=n:
    if(n%i==0):
      print i
    else:
       print("Please provide valid positive integer")
    i=i+1
printDivisors(10)
