# calculadora-losrulos 
Los participantes son Berenice Ortiz , Juan Sosa y ignacio temperini.
Este trabajo consiste en crear una calculadora con las siguientes funciones : multiplicacion  , division , resta y suma .
#/SUMA Y RESTA/ 
def suma (a, b): return = a + b

def resta (a, b): return = a - b

def main(): print ("---CALCULADORA SIMPLE---") print ("1 - suma") print ("2 - resta") print ("3 - multiplicacion") print ("4 - division")

opcion = input("elija una opcion: ")
if opcion == "1":
    a=float(input("primer numero: "))
    b=float(input("segundo numero: "))
    print ("resultado: ", suma(a, b)
else:
     if opcion == "2":
    a=float(input("primer numero: "))
    b=float(input("segundo numero: "))
    print ("resultado: ", resta a, b)
else:
     if opcion == "3":
           print ("funcion en desarrollo...")
else:
      if opcion == "4":
           print ("funcion en desarrollo...")
      else:
           print ("opcion invalida")
if__name__=="main": main ()
#/MULTIPLICACION Y DIVISION/ 
def multiplicar(a, b): resultado = a * b print "El resultado de la multiplicación es:", resultado return resultado

def dividir(a, b): if b == 0: print "Error: no se puede dividir por cero." return None else: resultado = a / b print "El resultado de la división es:", resultado return resultado

print " MULTIPLICACION " num1 = int(raw_input("Ingrese el primer numero para multiplicar: ")) num2 = int(raw_input("Ingrese el segundo numero para multiplicar: "))

multiplicar(num1, num2)
  
print "DIVISION " num3 = int(raw_input("Ingrese el primer numero para dividir: ")) num4 = int(raw_input("Ingrese el segundo numero para dividir: "))

dividir(num3, num4)

