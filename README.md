Solución de la Actividad 2: Estaciones del año

Me estaba enfrentando a la ambivalencia de dos alternativas para 
la solución de la actividad: **if-else** y **switch-case**. Una vez
analizado el predicamento, llegué a la conclusión de que 
**switch-case** sería la mejor alternativa, debido a la naturaleza de
extensas condiciones que demanda la actividad; en **switch-case** se
vería mucho más limpio y legible. Una vez establecido el modus
operandi, comencé a trabajar.

El primer paso fue crear la variable *mes*, la cual almacenaría
el mes ingresado. Acatando las instrucciones, le asigné 10 como
su valor predeterminado.

El tercer paso fue crear el susodicho **switch**, con la variable
*mes* como controlador. Fue en este punto cuando comenzó mi 
enfrentamiento con el segundo problema: todos los posibles
resultados tienen múltiples condiciones (tanto 12 como 1 y 2 dan
como resultado "invierno"). Entonces me pregunté: 

- Si cada **case** contiene un solo número como condición, 
¿entonces cómo puedo asignar múltiples condiciones a un solo
fragmento de código? -

Inicialmente, consideré la posibilidad de que me vería forzado a 
usar if-else. Esto no es lo que yo quería, sin embargo. 

- No, yo no soy ningún mediocre. Debo pensar en una manera... - 

Debido a mi usual desacato, me sentí determinado a cumplir mi 
objetivo. Entonces pensé. Y pensé. Hasta que di en el blanco.

- ¡Es verdad! - Recordé.

- La instrucción break cierra el bloque de código que pertenece
al **case**. Si este es el caso, omitir el **case** me permitiría ejecutar
un **case** dentro de otro.

Puse en práctica mi hipótesis para elucidar mi mente.

- ¡Eureka! -

Mis sospechas fueron confirmadas. Creé los cuatro tríos de **cases**
con los tres meses de cada estación, respectivamente. El truco
reside en dejar vacíos los primeros dos, incluso sin break, para
luego añadir la impresión del mensaje en el tercer mes, con break
incluido. Retomando el ejemplo anterior, los **cases** 12 y 1 se encuen-
tran completamente vacíos y uno después del otro, seguidos por el
**case** 2, el cual incluye el mensaje indicando que es invierno, mas
el break. De esta manera, los **cases** o meses 12, 1 y 2 imprimen "¡Es
invierno!" Repetí el proceso con el resto de estaciones y meses.


- ¡Ja, ja, ja, ja, soy un genio! Hora de enviar esto. -

Fue entonces cuando yo, el genio, me di cuenta de que casi olvido
agregar al final mi nombre y  mi carné, tal y como se me había
solicitado.

- Oh, cierto. -

FIN






 
