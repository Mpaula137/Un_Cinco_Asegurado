# Un_Cinco_Asegurado
Queremos lograr realizar y entregar un trabajo con una muy buena calidad para poder lograr y ser merecedores de un hermoso 5

## Grupo conformado por:

- Diego Alejandro Muñoz Penna

- Aaron suarez

 - Maria Paula MAchuca Hortua

Nos complace decir que nuestro grupo lleva por nombre PYTHONBROKES y a continuación mostrare nuestro logo

[![logo.jpg](https://i.postimg.cc/HL4kxVwv/logo.jpg)](https://postimg.cc/4Kyg24Fp)



## Primer punto : Python quiz
Quiz que debe tener un 90% de acertividad a la hora de hacerlo.

[![image.png](https://i.postimg.cc/pTSVBng0/image.png)](https://postimg.cc/ftxhzkWX)

## Segundo punto : Codigo 
Realice un programa que lea tres números reales y determine cuál es el mayor.

Explicación: Realizamos una investigación como para guiarnos, en youtube encontramos un código similar decidimos guiarnos con este.
Entendemos que al principio le damos la asignación a la variable "n" luego encontramos la acción de "input" la cual va a permitir al usuario interactuar con el código, luego establecimos las condiciones necesarias para que se diera la respuesta de cual número es mayor.


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
Archivo de codigo ejecutado en un archivo .py

[![image.png](https://i.postimg.cc/qRR6HJ8h/image.png)](https://postimg.cc/v1JZWd2b)



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

## Sexto punto: Vocales y Consonantes
Escriba un programa que solicite al usuario una letra y determine si es una vocal o una consonante.
print

```
print("Escriba una letra")
x = str(input())
if x =="a" or x =="e" or x =="i" or x =="o" or x =="a" or x =="u":
    print("la letra es una vocal")
else:
    print("la letra es una consonante")
```
## Septimo punto: Operaciones varias

Escriba un programa que pida 5 números reales y calcule las siguientes operaciones:

-El promedio
-La mediana
-El promedio multiplicativo (multilplica todos y luego calcula la raíz de la cantidad de operandos)
-Ordenar los números de forma ascendente
-Ordenar los números de forma descendente
-La potencia del mayor número elevado al menor número
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



## Sexto punto: Vocales y Consonantes

Escriba un programa que solicite al usuario una letra y determine si es una vocal o una consonante.

print



```

print("Escriba una letra")

x = str(input())

if x =="a" or x =="e" or x =="i" or x =="o" or x =="a" or x =="u":

    print("la letra es una vocal")

else:

    print("la letra es una consonante")

```

## Septimo punto: Operaciones varias



Escriba un programa que pida 5 números reales y calcule las siguientes operaciones:



-El promedio

-La mediana

-El promedio multiplicativo (multilplica todos y luego calcula la raíz de la cantidad de operandos)

-Ordenar los números de forma ascendente

-Ordenar los números de forma descendente

-La potencia del mayor número elevado al menor número

-La raíz cúbica del menor número

```

fg

```

## Octavo punto: Espectro electromagnético



Escriba un programa al que se le ingrese la frecuencia de una onda en hz y como salida arroje en que parte del espectro electromagnético se encuentra.

```

x: float

x= float(input("escriba la frecuencia en Hz"))

if x> (30.0)*(10)**(18):

    print ("Rayos gamma")

elif x> (30.0)*(10)**(15):

    print ("Rayos X")

elif x> (1.5)*(10)**(15):

    print ("Ultravioleta Extremo")

elif x> (7.89)*(10)**(14):

    print ("Ultravioleta Cercano")

elif x> (384)*(10)**(12):

    print ("Espectro Visible")

elif x> (120)*(10)**(12):

-La raíz cúbica del menor número
```
fg
```
## Octavo punto: Espectro electromagnético

Escriba un programa al que se le ingrese la frecuencia de una onda en hz y como salida arroje en que parte del espectro electromagnético se encuentra.
```
x: float
x= float(input("escriba la frecuencia en Hz"))
if x> (30.0)*(10)**(18):
    print ("Rayos gamma")
elif x> (30.0)*(10)**(15):
    print ("Rayos X")
elif x> (1.5)*(10)**(15):
    print ("Ultravioleta Extremo")
elif x> (7.89)*(10)**(14):
    print ("Ultravioleta Cercano")
elif x> (384)*(10)**(12):
    print ("Espectro Visible")
elif x> (120)*(10)**(12):
    print ("Infrarojo cercano")
elif x> (6.00)*(10)**(12):
    print ("Infrarojo medio")
elif x> (300)*(10)**(9):
    print ("Infrarojo Lejano/Submilimetrico")
elif x> (3)*(10)**(8):
    print ("Microondas")
elif x> (300)*(10)**(6):
    print ("Ultra Alta Frecuencia-Radio")
elif x> (30)*(10)**(6):
    print ("Muy Alta Frecuencia-Radio")
elif x> (1.7)*(10)**(6):
    print ("Onda Corta - Radio")
elif x> (650)*(10)**(3):
    print ("Onda Media - Radio")
elif x> (30)*(10)**(3):
    print ("Onda Larga - Radio")
elif x< (30)*(10)**(3) and x>0:
    print ("Muy Baja Frecuencia - Radio")
elif x<0:
    print ("No existen frecuencias menores a 0")

```
## Noveno punto: Capitales
Escriba un programa que reciba el nombre en minúsculas de un país de America y retorne la ciudad capital, si el país no pertenece al continente debe arrojar país no identificado.
```
jik
```

## Decimo punto: Dada una distancia varias operaciones

Escriba un programa que dada una distancia calcule:

-El tiempo que le tomaría a la luz recorrer la distancia.
-El tiempo que le tomaría al sonido (en el aire) recorrer la distancia.
-El tiempo que le tomaría al vehiculo comercial más veloz recorrer la distancia.
-El tiempo que le tomaría a Bolt recorrer la distancia.

```
gds
```

