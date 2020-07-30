import math
a = float(input(" o valor da A "))
b = float(input(" o valor do B "))
c = float(input(" o valor do C "))

delta = b**2 - 4*a*c

if (delta < 0):
    print(" nao ha solucao {} " .format(delta))
elif (delta == 0):
    resul2 = (-b // 2*a)
    print(" duas raizes iguais que tem o valor de {} " .format(delta))
    print(" resultado {} ".format(resul2))
elif (delta > 0):
    x1 = (-b + math.sqrt(delta)) / (2*a)
    x2 = (-b - math.sqrt(delta)) / (2*a)
    print(" resultado x1 {} " .format(x1))
    print(" resultado x2  {} " .format(x2))
    print(" duas raizes reais e diferentes {}  " .format(delta))
        
