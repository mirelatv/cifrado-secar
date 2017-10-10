
                               # pseudoicodigo

# Funcion cipher
  * Crear variable (q)
	    -solicitamos PROMPT /cual es tu nombre/
	    -Informacion de retorno info de usuario
  * (WHILE)/ MIENTRAS QUE
      -  Si el Contenido es vacio o numerico    >> solicitamos al usuario ingresar datos validos
      -  Si el contenido no es vacio
	    >  for/ recorro los indices de  la variable/ q/
	   -   q/lo convierto en mayusculas

  * Crear variable qM
	    - qM <- /q.toUpperCase/
	    - for  /recorro qM/
  * Generamos  nuevas variables /var str/var np( nueva posision) /, var lc (letterCifher)
	     - formula/ Ascci
	     -np <- np/ascci
       - lc <- np(String.fromChardode)
	     -str <-  (+)lc
## Retornamos al usuario alert de nombre cifrado

# Funcion decipher(str)
  * creando var decipherWord=""/variables     retroPosition,variable  letterCesar
        -recorriendo str
        - variables retroPosition /str.charCodeAt(h)+65-33)%26+65
        -  variable  letterCesar/ String.fromCharCode(retroPosition);
        -decipherWord += letterCesar;


## alerta al usuario de  su nombre  ( cifrado y decifrado)

//llamando  funciones

decipher(cipher());

![](https://fotos.subefotos.com/ed7869ab50df24f9b218e258c99342f6o.png)
