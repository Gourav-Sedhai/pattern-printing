# pattern-printing
a question from today's event.
pattern printing using for loop using python.
def contalpha(n):
    num = 65
    for i in range(1, n):
        for j in range(1, 2*i-1):
            if j<=i:
                num = 64 + j
                ch = chr(num)
                print(ch, end=" ")
                #num = num + 1
            else:
                k = 1
                num = 65 + j
                ch = chr(num)
                k = k + 1
                #num = num + 1
        print("\r")
n = 6
contalpha(n)        
