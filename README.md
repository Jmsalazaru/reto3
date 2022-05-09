# reto3
jelmi




id=str(input("ingrese su CDIA: "))


def verify (c):
  if len(c)== 10 and c == str and c[5] == "@" and c[0] != c[9] and "+" in c and c.count("k")< 3  and  (("?" in c) or ("=" in c) or ("&" in c)): 
    return c
  else:
    return ("CDIA INVÁLIDO")
    
  

def verify2 (c):
  if len(c)== 11:
   if c == str:
    if c[7] == "@":
      if c[0] != c[11]:
        if "+" in c:
          if c.count("k")< 3:
            if (("?" in c) or ("=" in c) or ("&" in c)):
              return (c)
  else:
    print ("Cdia inválido")
    
    
"""revision=verify(id)
print (revision)  """         

fechaNacimiento=int(input("Cuál es tu fecha de nacimiento en formato DD/MM/AAAA "))
edad = 2022-AAAA

if (edad > 12):
  alias=Input("Cuál es tu alias? ")
  if len(alias)>5 and " " not in alias :
    hasPlayed=str(input("¿Has jugado world of worldcraft ASCII?, responde con un (Si/No)") 
  if (hasPlayed == "Si"):
                  preguntaNivel=str(input("hasta que nivel llegaste?" ))
else:
  print(No puedes jugar!)



if edad<16 and hasPlayed == "Si":
  nivelAsignado = printreguntaNivel+2
  else nivelAsignado=preguntaNivel
  
                  
  
                  
  

funcionMundo(lvl, age, hasPlayed):
if hasPlayed == "No" and 12 < age< 20:
  return ("Se te asigna al mundo 1")
elif hasPlayed == "Si" and lvl < 50  and 12 < age< 20:
  return ("Se te asigna al mundo 2")
elif hasPlayed == "Si" and lvl >= 50  and 12 < age< 20:
  return ("Se te asigna al mundo 3")
elif hasPlayed =="No" and age > 20: 
  return ("Se te asigna al mundo 4")
elif hasPlayed == "Si" and lvl < 50  and age > 20:
  return ("Se te asigna al mundo 5")
elif hasPlayed == "Si" and lvl >= 50  and age > 20:
  return ("Se te asigna al mundo 5")
  
  
  



 


  
 





