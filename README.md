print("Enter n")
n=int(input())
print("Enter m")
m=int(input())
print(f"The multiplication table of {n} is")
for i in range(1,m+1):
    print(f"{i}*{n}={i*n}")

