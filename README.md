# Taller1-Punto8

Se desea crear un esquema para validar XML en los que haya un solo elemento raíz 
llamado cantidad en el que se debe poner siempre un atributo «divisa» que indique en 
qué moneda está una cierta cantidad. El atributo divisa siempre será una cadena y la 
cantidad siempre será un tipo numérico que acepte decimales (por ejemplo float ). El 
esquema debe validar los archivos siguientes:
<cantidad divisa="euro">20</cantidad>
<cantidad divisa="dolar">18.32</cantidad>
Pero no debe validar ninguno de los siguientes:
<cantidad>20</cantidad>
<cantidad divisa="dolar">abc</cantidad>
