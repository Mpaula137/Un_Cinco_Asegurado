# Un_Cinco_Asegurado 馃嵖馃殌
Queremos realizar y entregar un trabajo con una muy buena calidad para poder lograr y ser merecedores de un hermoso 5

## Grupo conformado por:

- Diego Alejandro Mu帽oz Penna

- Aaron Alejandro Suarez Bonilla

 - Maria Paula Machuca Hortua

Nos complace decir que nuestro grupo lleva por nombre PYTHONBROKES y a continuaci贸n mostrare nuestro logo

[![logo.jpg](https://i.postimg.cc/HL4kxVwv/logo.jpg)](https://postimg.cc/4Kyg24Fp)



## Primer punto : Python quiz馃槑
Quiz que debe tener un 90% de acertividad a la hora de hacerlo.

[![image.png](https://i.postimg.cc/pTSVBng0/image.png)](https://postimg.cc/ftxhzkWX)

## Segundo punto : Codigo 
Realice un programa que lea tres n煤meros reales y determine cu谩l es el mayor.

Explicaci贸n: Realizamos una investigaci贸n como para guiarnos, en youtube encontramos un c贸digo similar decidimos guiarnos con este.
Entendemos que al principio le damos la asignaci贸n a la variable "n" luego encontramos la acci贸n de "input" la cual va a permitir al usuario interactuar con el c贸digo, luego establecimos las condiciones necesarias para que se diera la respuesta de cual n煤mero es mayor.


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
Archivo de codigo ejecutado en un archivo .py:

[![image.png](https://i.postimg.cc/qRR6HJ8h/image.png)](https://postimg.cc/v1JZWd2b)



## Tercer punto: Par o impar 馃
Realice un programa que lea un n煤mero enteros y determine si es par o impar.
Explicaci贸n: Asignaremos la variable y analizando el problema sabemos que un n煤mero es par cuando es divisible por 2 asi que colocamos un modulo el cual nos dice que s铆 el resultado es igual a 0 este seria un numero par.

```
n: int
n = int(input("ingrese el numero:"))
if n % 2 == 0 :
    print("es un numero par")
else:
    print("es un numero impar")  
```
 Archivo de codigo ejecutado en un archivo .ipynb :
 
 [![Captura-de-pantalla-2023-03-13-153406.png](https://i.postimg.cc/Vs9rxR9D/Captura-de-pantalla-2023-03-13-153406.png)](https://postimg.cc/XXJYF9zC)
 


## Cuarto punto: M煤ltiplos馃搻馃搹
Realice un programa que lea dos n煤meros reales y determine si el primero es m煤ltiplo del segundo

Explicaci贸n: Asignamos la variable con su interacci贸n de una vez, luego con un m贸dulo como operaci贸n designada encontraremos los multiplos requeridos.
```
x = float(input("escoge tu primer numero "))
y = float(input("escoge tu segundo numero "))
if x % y == 0:
  print ("el primer n煤mero es m煤ltiplo del segundo")
else: 
  print("el primer n煤mero no es m煤ltiplo del segundo")
```
Archivo de codigo ejecutado en un archivo .py:

[![image.png](https://i.postimg.cc/c4vxyDrJ/image.png)](https://postimg.cc/LnMKj3kd)


## Quinto punto: Codigo馃枼
Realice un programa que lea tres n煤meros reales y determine si la suma de los dos primeros es mayor, menor o igual que el tercer n煤mero.
Explicaci贸n: Asignamos la variable, luego determinamos el condicional requerido para lograr identificar si la suma es mayor que el tercer n煤mero, sabemos que usando los operadores decignamos la suma luego con el signo ">" sabemos que el interprete nos dira si la suma es mayor que el tercero.

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
 Archivo de codigo ejecutado en un archivo .ipynb :
 
 [![image.png](https://i.postimg.cc/0N3DNyrn/image.png)](https://postimg.cc/R37Ns97J)
 

## Sexto punto: Vocales y Consonantes馃懆鈥嶐煆煈┾?嶐煆?
Escriba un programa que solicite al usuario una letra y determine si es una vocal o una consonante.

Explicaci贸n: Elegimos elegir el "print" para interactuar luego definimos a x como una cadena y en el condicional colocamos las vocales y si no se imprime una letra de estas es consonante.

```
print("Escriba una letra")
x = str(input())
if x =="a" or x =="e" or x =="i" or x =="o" or x =="a" or x =="u":
    print("la letra es una vocal")
else:
    print("la letra es una consonante")
```
Archivo de codigo ejecutado en un archivo .py:

[![image.png](https://i.postimg.cc/L8HJ1cD8/image.png)](https://postimg.cc/tYMR0m8K)


## Septimo punto: Operaciones varias鉃曗灃

Escriba un programa que pida 5 n煤meros reales y calcule las siguientes operaciones:

-El promedio

-La mediana

-El promedio multiplicativo (multilplica todos y luego calcula la ra铆z de la cantidad de operandos)

-Ordenar los n煤meros de forma ascendente

-Ordenar los n煤meros de forma descendente

-La potencia del mayor n煤mero elevado al menor n煤mero
```

n1: int
n2: int
n3: int
n4: int
n5: int
n1= int(input("ingrese el numero 1:"))
n2=int(input("ingrese el numero 2:"))
n3= int(input("ingrese el numero 3:"))
n4= int(input("ingrese el numero 4:"))
n5= int(input("ingrese el numero 5:"))
list= [n1, n2, n3, n4, n5]
prom= (n1+n2+n3+n4+n5) / 5
print ("este es su promedio:",prom)
import math
x = 5
prom_multi= (n1*n2*n3*n4*n5) / math.sqrt(x)
print ("Este es el promedio multiplicativo:", prom_multi)
orde= list.sort()
print("Aca esta tu lista en orden ascendente:", list)
orde_2= list.sort(reverse = True)
print("Aca esta tu lista en orden descendente:", list) #falta la mediana
```

 Archivo de codigo ejecutado en un archivo .ipynb :



## Octavo punto: Espectro electromagn茅tico馃搱


Escriba un programa al que se le ingrese la frecuencia de una onda en hz y como salida arroje en que parte del espectro electromagn茅tico se encuentra.

Explicaci贸n: Buscamos todos los criterios y operaciones especializadas para poder hallar la frecuencias y las colocamos en forma de condici贸n.

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
Archivo de codigo ejecutado en un archivo .py:

[![image.png](https://i.postimg.cc/yYrGgZ0Q/image.png)](https://postimg.cc/ZCpHX07p)

## Noveno punto: Capitales 鉁堬笍
Escriba un programa que reciba el nombre en min煤sculas de un pa铆s de America y retorne la ciudad capital, si el pa铆s no pertenece al continente debe arrojar pa铆s no identificado.
Explicaci贸n: Al principio tuvimos dudas sobre este pero buscamos guias y encontramos que en primer lugar tenemos que crear un diccionario donde estaran los paises y capitales luego creamos la condici贸n a cumplir en donde colocaremos que si el pais esta en la capital, imprimimos el pais y la capital.

```
capital_ciudad = {
  "argentina": "buenos aires",
  "bolivia": "la paz",
  "brasil": "brasilia",
  "canada": "ottawa",
  "chile": "santiago",
  "colombia": "bogota",
  "costa rica": "san jose",
  "cuba": "la habana",
  "ecuador": "quito",
  "estados unidos": "washington",
  "guatemala": "ciudad de guatemala",
  "haiti": "puerto pr铆ncipe",
  "honduras": "tegucigalpa",
  "jamaica": "kingston",
  "m茅xico": "ciudad de m茅xico",
  "nicaragua": "managua",
  "panam谩": "ciudad de panam谩",
  "paraguay": "asunci贸n",
  "per煤": "lima",
  "rep煤blica dominicana": "santo domingo",
  "uruguay": "montevideo",
  "venezuela": "caracas"
}

pais = input("Ingrese el nombre del pa铆s en min煤sculas: ")

if pais in capital_ciudad:
  capital = capital_ciudad[pais]
  print("La ciudad capital de", pais.title(), "es", capital.title())
else:
  print("Lo siento, el pa铆s", pais.title(), "no se encuentra en la lista.")
```
 Archivo de codigo ejecutado en un archivo .ipynb :

[![Captura-de-pantalla-2023-03-13-153334.png](https://i.postimg.cc/WzS4h5XV/Captura-de-pantalla-2023-03-13-153334.png)](https://postimg.cc/gLXp7qCt)

## Decimo punto: Dada una distancia varias operaciones 馃馃殫

Escriba un programa que dada una distancia calcule:

-El tiempo que le tomar铆a a la luz recorrer la distancia.

-El tiempo que le tomar铆a al sonido (en el aire) recorrer la distancia.

-El tiempo que le tomar铆a al vehiculo comercial m谩s veloz recorrer la distancia.

-El tiempo que le tomar铆a a Bolt recorrer la distancia.
 
 Explicaci贸n: Primero declaramos que tipo es nuestra variable(distancia) luego damos la opci贸n al usuario de ingresar la distacia que le sea de su agrado, despues decidimos dar el valor a cada velocidad que usaremos despues en cada formula para hallar el tiempo, luego de que ya esten ponemos el procedimiento e imprimos el resultado correspondiente asi sucesivamente.

```
Distancia=float(input("Ingrese la distancia deseada en metros:"))
Vel_Lu=299792.458
Vel_So=343
Vel_Veh=136.2444
Vel_Bold=12.24
Tiempolu=(Distancia/Vel_Lu)
print ("El tiempo para que la luz recorra la distancia", Distancia, "es de:" +str (Tiempolu) + " segundo(s)")
TiempoSo=(Distancia/Vel_So)
print("El tiempo para que el sonido recorra la distancia", Distancia,"es de:" +str(TiempoSo)+ "segundo(s)")
TiempoVeh=(Distancia/Vel_Veh)
print("El tiempo para que el vehiculo recorra la distancia",Distancia, "es de:" +str(TiempoVeh)+ "segundo(s)")
TiempoBold=(Distancia/Vel_Bold)
print("El tiempo para que Bold recorra la distancia", Distancia, "es de:" +str(TiempoBold)+ "segundo(s)")
```
Archivo de codigo ejecutado en un archivo .py:

[![image.png](https://i.postimg.cc/905frhL9/image.png)](https://postimg.cc/bDgPBKcY)

# Hemos llegado al fin.
esperamos que complazca todos los punto calificables y poder obtener una de las mejores notas. 馃専
