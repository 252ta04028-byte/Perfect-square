import math

n = int(input("Enter a number: "))

if math.isqrt(n) ** 2 == n:
    print("Perfect Square")
else:
    print("Not a Perfect Square")
