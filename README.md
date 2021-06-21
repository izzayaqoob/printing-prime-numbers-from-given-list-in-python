# printing-prime-numbers-from-given-list-in-python
for x in range(2,1000):
    PRIME=True
    for j in range(2,x):
        if (x%j)==0:
            PRIME=False
    if PRIME==True:
        print(x)
