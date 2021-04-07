n = int(input("Enter the number of terms:"))
i = 0
j = 1
print(i)
print(j)
for a in range(2,n):
    s = i + j
    print(s)
    i = j
    j = s
