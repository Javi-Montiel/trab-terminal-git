# Mi laboratorio de terminal y git
Autor: Javier Montiel Solis
MatIA: recuento de pinzas con datos sinteticos.
Ejecucion: 
#(cabe recalcar que al principio use un codigo distinto, hecho por mi y totalmente funcional, pero completando el trabajo en las anteriores clases lo cambie por el que se nos dio en clase debido a una confusion mia)

#Creo unos datos con instrumentos medicos
instrumentos = ["pinza", "tijera", "pinza"]
esperadas = 2
observadas = 0

#Recorro la lista elemento por elemento
for instrumento in instrumentos:
    if instrumento == "pinza":
        observadas = observadas + 1

print("Pinzas esperadas:", esperadas)
print("Pinzas observadas:", observadas)

#Comparo finalmente el recuento final con el resultado esperado
if observadas < esperadas:
    print("Resultado: faltan pinzas")
elif observadas > esperadas:
    print("Resultado: sobran pinzas")
else:
    print("Resultado: coincide")
    
IA: Si, para refrescar memoria con Python ya que se me habian ido algunos detalles del curso anterior. 

## Comprobacion
He probado los casos: coinciden las pinzas.
