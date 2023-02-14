# flujodecontrol
print("**** Sistema de Becas *****")
print("                                                                ")
distaciadecasa=int(input("Intrudzca la distancia de vivienda del solicitante :"))
print("                                                                ")
numerodehermanos=int(input("Intruduzca la cantidad de hermanos del solicitante: "))
print("                                                                ")
Salariodelpadre=int(input("intruduzca el total de igresos del solicitante:  "))
print("                                                                ")
print("La distancia es:"+str(distaciadecasa))
print("El numero de hermanos es: "+str(numerodehermanos))
print("Total ingresos: "+str(Salariodelpadre))
print("                                                                ")
if distaciadecasa> 40 and numerodehermanos>2 or Salariodelpadre <  2000:
    print("Eres Candidato a Beca")
else:
    print("Lo siento no cumples con los requisitos ")




 #1.	Crear una variable que contenga un elemento del conjunto de números enteros y luego imprimir por pantalla si es mayor o menor a cero
v=4
if (v<0):
    print(" es un número negativo")
elif (v>0):
    print("es un número positivo")
else:
  print("es cero");
# 2.	Crear dos variables y un condicional que informe si son del mismo tipo de dato
x=[1,2,3 ]
yfloat="0.0"
if ((x)!=(yfloat)):
    print ("son diferentes: ")
    print(type(x))
    print(type(yfloat))
elif((x)==(yfloat)):
   print("son del mismo tipo")
   print(type(x))
   print(type (yfloat))
else:
   print("indefinido")
 

#3.	Para los valores enteros del 1 al 20, imprimir por pantalla si es par o impar
list1=  [1,2,3,4,5,6]
 # iterating each number in list
for num in list1:
    # checking condition
    if num % 2 == 0:
              print(num, end = " \n " )         
    elif  num % 2 != 0:
       print(num, end = "    ")
#4.	En un ciclo for mostrar para los valores entre 0 y 5 el resultado de elevarlo a la potencia igual a 3       
for i in range(5):
 print(i**3)
#5.	Crear una variable que contenga un número entero y realizar un ciclo for la misma cantidad de ciclos
 v=10
for i in range(v):
 print("esto es un ciclo de 10 porque v=10 "+str(i+1))


#ciclo for recorriendo espacios 
for i in ["","","",""]:
  print(5)
#recorriendo buscando un caracter para ofrecer un mensaje
email=0
miemail=input("Introduzca su email: ")

for i in miemail:
    if (i=="@" or i=="."):
        email=email+1


if  email==2:
    print("email es correcto")
else:
    print(" email es incorrecto")



