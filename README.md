# later
code we will learn &amp; run in the future

# perfect square number in the given range
i=1
t=50
#int(input('enter the value '))
for j in range(1,t+1):   # range from 1 to t
    while(i<=((j//2)+1)):
        if(i**2==j):
            print(j)
        i+=1
    i=1
