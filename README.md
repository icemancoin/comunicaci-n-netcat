 - Entre dispositivos linux conectados en la misma red.


 - Abriremos una terminal en uno de los dispositivos, lanzamos el comando ifconfig y anotaremos la dirección ip asignada: 

  $:/   192.168.1./1-250     . Guardamos/Recordamos.


 - Escribimos en una nueva línea de comando:

  $:/   nc -l -v -p 1234   

  .Y pulsamos intro automáticamente esta abierto el enlace de comunicación.


 - En otro dispositivo, conectado a la misma red abrimos terminal:

  $:/   nc -v ((ip de la máquina de enlace)) 1234       .
  .Y intro, separamos con un espacio e introducimos ip sin parentesis, espacio y 1234.

 - Estamos dentro entre dispositivos. 


 - Repetimos esto en nuevas ventanas entre nuevos dispositivos tantas veces necesitemos, tendremos comunicación interna.
   
 - Privada en nuestra área de trabajo, estudio o hogar.
