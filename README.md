# silver-train
from math import pi
def OKI(n):
    try:
       n=int(n)
		except:
		   n=OKI(input("Caracter no valido: "))
		return n
def OKP(n):
    if n!=("pi"):
		   try:
			    n=float(n)
			 except:
			    n=OKP(input("Caracter no valido: "))
		else:
		   n=pi
		return n
def OK(n):
    try:
		   n=float(n)
		except:
		   n=OK(input("Caracter no valido: "))
		return n
def ns(c):
    while c!=("s") and c!=("n"):
		  print(chr(7));c=input("Escribir solo \'n\' o \'s\' segun su opción: ")
