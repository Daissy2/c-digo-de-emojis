candado="pu,ya,es"
heroe="!Bienvenido, heroòe!"
villano="¡acceso denegado"
def detective(clave):
  return clave == candado
usuario= input("ingresa la clave")
if detective( usuario):
  print(heroe)
else:
  print(villano)
