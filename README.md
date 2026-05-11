# Arranging-coins
n = int(input("Enter number of coins: "))
i = 1
while n >= i:
    n -= i
    i += 1
print("Complete rows:", i - 1)
