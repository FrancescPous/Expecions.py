# Expecions.py

# Excepcions 1 

try:
    Numero1 = float(input ("Digues un numero:"))
    Numero2 = float(input ("Digues un numero:"))
    resultat = Numero1 / Numero2
    print(resultat)
except:
    print("ERROR")

# Excepcions 2

try:
    num1 = int(input ("Digues un numero:"))
except:
    print("ERROR")


# Excepcions 3

entrada = input("Introduiex un numero: ")
try:
    numero = int(entrada)
    print("El numero convertit es:", numero)
except:
    print("S'ha produit un error en la converisó del numero")

# Excepcions 4

try:
    valor1 = float(input("Introdueix un numero:"))
    valor2 = float(input("Introudeix un numero:"))
    resultat= valor1 + valor2
    print("res ", resultat)
except:
    print("ERROR")

# Excepcions 5

llista = [1,3,5,6]
try:
    num = int(input("Fica un numero de la llista:"))
    print(llista[num])
except:
    print("ERROR")
