## PROGAMAÇOES
### PYTHON


``` 
    | Celsius para fahrenheit |
celsius = float(input("Digite a temperatura em Celsius: "))

fahrenheit = (celsius * 9/5) + 32

print(celsius, "graus Celsius é equivalente a", fahrenheit, "graus Fahrenheit.")
```

```
    | Tabuada de 1 ao 10 |
while True:
n = input("Digite o número que deseja obter a tabuada de 1 à 10 (ou 'E' para sair) ")

if n.upper() == 'E':
    break

n = int(n)

if n in range(1,11):
    for i in range(1, 11):
        print(f"{n} x {i} = {n * i}")
else:
    print(f"Que parte do '1 à 10' você não entendeu?")while True:
```