# Un_Cinco_Asegurado

## Primer punto : Python quiz
Quiz que debe tener un 90% de acertividad a la hora de hacerlo.

[![image.png](https://i.postimg.cc/pTSVBng0/image.png)](https://postimg.cc/ftxhzkWX)

## Segundo punto : Codigo 
Realice un programa que lea tres números reales y determine cuál es el mayor.

```
n: float
n1 = float (input("ingrse el primer numero:"))
n2 = float (input("ingrese el segundo numero:"))
n3 = float (input("ingrese el tercer numero"))
if n1 > n2 and n1 >n3 :
    print("el numero mayor es:",n1)
elif n2 > n1 and n2 > n3 :
    print("el numero mayor es:",n2)
elif n3 > n1 and n3 > n2 :
    print("el numero mayor es:",n3)
```
## Tercer punto: Par o impar
Realice un programa que lea un número enteros y determine si es par o impar.

```
n: int
n = int(input("ingrese el numero:"))
if n % 2 == 0 :
    print("es un numero par")
else:
    print("es un numero impar")  
```


## Cuarto punto: Múltiplos
Realice un programa que lea dos números reales y determine si el primero es múltiplo del segundo

```
x = float(input("escoge tu primer numero "))
y = float(input("escoge tu segundo numero "))
if x % y == 0:
  print ("el primer número es múltiplo del segundo")
else: 
  print("el primer número no es múltiplo del segundo")
```

## Quinto punto: Codigo
Realice un programa que lea tres números reales y determine si la suma de los dos primeros es mayor, menor o igual que el tercer número.

```
n: float
n1= float(input("inserte el primer numero:",))
n2= float (input("nserte el segundo numero:"))
n3= float (input("inserte en tercer numero:"))
if (n1+n2) > n3:
    print("La suma es mayor a:",n3)
elif (n1+n2) < n3:
    print("la suma es menor a:",n3)
elif (n1+n2) == n3:
    print("la sumas es igual a:",n3)
```
