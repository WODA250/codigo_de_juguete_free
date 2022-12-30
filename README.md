# codigo_de_juguete_free

#secuencia fibonaci con bucle for

n = int(input("coloque su numero final: "))

a = (-1)  #inicia desde menos 1 para que aparezca el 0
b = 1

for i in range(n +
               1):  #se le suma 1 para que cuente todos los numeros menos el 0
  i = a + b
  a = b
  b = i
  print(i)
