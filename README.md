# RETO-4

# ¡PYTHON FC!

<details>
  <summary>ESCUDO</summary>
  
  [![PYTHON-F-C-B.jpg](https://i.postimg.cc/1Xpw71f0/PYTHON-F-C-B.jpg)](https://postimg.cc/jnSDC96C)

</details>

# 1 

```ruby
x : int
x = int(input("Ingrese un número entero: "))

if 97 <= x <= 122:
    if x == 97 or x == 101 or x == 105 or x == 111 or x == 117:
        print("El número si corresponde al código ASCII de una vocal minúscula.")
    else:
        print("El número no corresponde al código ASCII de una vocal minúscula.")
else:
    print("El número no corresponde al código ASCII de una vocal minúscula.")
```

# 2

```ruby

caracter = input("Ingrese un carácter: ")


if caracter in ['0', '2', '4', '6', '8']:
    print("El código ASCII del primer carácter es par.")
elif caracter in ['1', '3', '5', '7', '9']:
    print("El código ASCII del primer carácter no es par.")
else:
    print("El carácter ingresado no es un dígito.")
```

# 3 

```ruby

caracter = input("Ingrese un carácter: ")

if caracter >= '0' and caracter <= '9':
    print("El carácter ingresado es un dígito.")
else:
    print("El carácter ingresado no es un dígito.")
```

# 4

```ruby
x : float

x = float(input("Ingrese un número real: "))


if x > 0:
    print(f"El número {x} es positivo.")
elif x < 0:
    print(f"El número {x} es negativo.")
else:
    print(f"El número {x} es cero.")

```

# 5

```ruby
centro_x : float
centro_y : float
radio : float

centro_x = float(input("Ingrese la coordenada x del centro del círculo: "))
centro_y = float(input("Ingrese la coordenada y del centro del círculo: "))


radio = float(input("Ingrese el radio del círculo: "))


punto_x = float(input("Ingrese la coordenada x del punto: "))
punto_y = float(input("Ingrese la coordenada y del punto: "))


distancia_al_centro = ((punto_x - centro_x) ** 2 + (punto_y - centro_y) ** 2) ** 0.5


if distancia_al_centro < radio:
    print("El punto pertenece al interior del círculo.")
elif distancia_al_centro == radio:
    print("El punto pertenece a la circunferencia del círculo.")
else:
    print("El punto no pertenece al interior del círculo.")
```

# 6

```ruby
lado1 : float
lado2 : float
lado3 : float

lado1 = float(input("Ingrese la longitud del primer lado: "))
lado2 = float(input("Ingrese la longitud del segundo lado: "))
lado3 = float(input("Ingrese la longitud del tercer lado: "))


if lado1 + lado2 > lado3 and lado1 + lado3 > lado2 and lado2 + lado3 > lado1:
    print("Se puede construir un triángulo con las longitudes dadas.")
else:
    print("No se puede construir un triángulo con las longitudes dadas.")

```
