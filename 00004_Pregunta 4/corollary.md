A) =Espacios(sustituir(A1,carácter(160),””))
	
B) =Espacios(Sustituir(A1,Carácter(160),” “))

	**CORREECTO**: para el caso de ORACIONES siempre debe haber un ESPACIO entre cada palabra y lo que hace esta función es lo siguiente: sustituye el carácter 160 por un Espacio. Entonces, posiblemente estén quedando espacios demás en la oración. Por ejm: “Pedro      lava la                   Tina”
  
  Sin Embargo, todas esas brechas son solo ESPACIOS mas no Caracteres 160, es por eso que se le coloca como función final “=ESPACIOS” ya que este quita el espacio (si es que lo hay) inicial, para que comience con una palabra o letra, y quita los espacios demás entre las palabras y finalmente, quita el espacio final de la oración. 

C) =sustituir(sustituir(A1,Carácter(160),” “),” “,””)

D) N.A