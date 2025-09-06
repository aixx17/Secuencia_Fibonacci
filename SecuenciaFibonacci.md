Secuencia Fibonacci
```
print("Secuencia de Fibonacci")
num = int(input("Número límite de secuencia: "))

a, b = 1, 0

while num > 0:  
    print(b)
    a, b = b, a + b 
    num -= 1
