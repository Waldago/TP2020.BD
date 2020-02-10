# TP2020.BD

Trabajo Practico
----------------

El municipio de la ciudad de Mar del Plata nos encarga el diseño de una nueva base de datos para registrar 
información relacionada con las propiedades y sus correspondientes impuestos inmobiliarios.
Se nos solicita definir la base de datos donde se almacenará la información de cada uno de las propiedades
existentes en la ciudad. De cada una de ellas se registra el código catastral, la calle, el número, el código
postal y los datos de sus dueños. 
Si los dueños son personas fisicas se registra su número de documento, nombre, apellido y dirección legal a donde
enviarle impuestos y cartas. 
Si los dueños son empresas se registra el numero de CUIT, la razón social, número de documento, nombre y apellido 
del director de la empresa y dirección legala donde enviarle impuestos y cartas. 
De cada propiedad se almacenan cada una de los impuestos que deben pagarse contándose con la fecha del primer 
vencimiento, del segundo vencimiento, el importe al primer vencimiento y el importe al segundo vencimiento. 
Tambien se registran los pagos de cada uno de estos impuestos registrándose la fecha de pago, entidad donde 
se pago. Monto no hace falta ya que corresponde con el importe del vencimiento. 
En caso de que un impuesto quedase impago, se generara un aviso de incumplimiento que le sera enviado a los 
dueños intimandolos a regularizar la situacion.

Se solicita generar una URL donde se presentara la resolucion del trabajo. 
En la misma debe especificarse los apellidos y nombres de los integrantes del grupo, enunciado y resolucion.

Debe adjuntarse la resolucion de los siguientes puntos:
1) Generar el modelo entidad interralacion correspondiente
2) A partir del MEI, generar el modelo relacional correspondiente. Identificar PK y FK de cada relacion.
3) Construir el diagrama de entidad-relacion (DER) correspondiente. Identificar PK y FK de cada relacion.
4) Resolver en algebra relacional las siguientes consultas:
 a) Obtener los datos completos de los codigos postales que no tienen todos los impuestos pagos del año 2015
 b) Obtener los datos completos de los dueños que que solo pagaron una cuota durante 2019
