# practica4
-> flujos de información
cuadrados son tareas [sign in] [search products] ...
<X> gates o puertas, toma decisiones y define bucles 
X es or en gates.
+ es una puerta concurrente, and

Para hacerlo en maude tenemos un token que va desplazandose entre flujos. 
En el and hay varios tokens.
Un sistema = (conjunto de tokens, (flujo, puertas y tareas) , tiempo) 
Los temporizadores están todos en los tokens.

mas dificil = delta , EMT 

recursos:
clerk
worker
delivery man
car
droone

EL mte es el mínimo tiempo de los tokens que no están esperando en el merge.

Son Requerimientos para poder realizar una tarea además de que el temporizador del token esté a 0

search initial => ( < Process | ... >) such that T < 100 ^ ...

Para ello se modifica tick siempre que quieras acotar time
crl [tick]______ => ____ if T < 100