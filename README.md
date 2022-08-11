# InformeLaboratorio


1. OBJETIVOS



2. MARCO TEÓRICO 

**TEOREMA DE SUPERPOSICIÓN**

El teorema de superposición, en circuitos eléctricos, establece que el voltaje entre dos puntos, o la corriente a través de ellos, es la suma algebraica de los voltajes (o de las corrientes si es el caso), debidos a cada fuente, como si cada una actuara de manera independiente.

Este teorema permite analizar circuitos lineales que contengan más de una fuente independiente, ya que solamente se requiere calcular la contribución de cada una por separado.

* Cuando en un circuito se utilizan múltiples fuentes, el teorema de superposición proporciona un método de análisis.
* Es aplicable porque hay una relacion lineal entre corriente y tensiones, con fuentes dependientes.
* Solo puede utilizarse cuando las funciones de control son externas al circuito que tiene las fuentes.
* Las fuentes de tensón se suprimen sustituyendolas por un cortocircuito.
* Las fuentes de intensidad se suprimen por un circuito abierto.
* La superposición no puede aplicarse directamente para el calculo de la potencia.

**Pasos para aplicar el teorema de S  uperposición**

1.-Dejar una fuente de voltaje (o de corrient) a la vez en el circuito y reemplazar cada una de las demás fuentes de voltaje (o de corriente) con su resistencia interna. Para fuentes ideales, un corto representa resistencia interna de cero y una abertura representa resistencia interna infinita.

2.-Determinar la corriente (o el voltaje) particular que se desea justo como si hubiera solo una fuente en el circuito.

3.-Tomar la siguiente fuente que haya en el circuito y repetir los pasos 1 y 2. Hacer esto con cada una de las fuentes.

4.-Sumar algebraicamente las corrientes producidas por cada fuente individual para encontrar la corrientereal en una rama dada. (Si las corrientes estan en la misma direccion, se suman. Si estan en direcciones opuestas, se restan y la direccion de la corriente resultante será la misma que la presentada por la cantidad más grande de las cantidades originales.) Una vez determinada la corriente, ya se puede calcular el voltaje mediante la ley de Ohm.

**TEOREMA DE MÁXIMA TRASFERENCIA DE POTENCIA**}

El teorema de transferencia de potencia maxima nos dice que la resistencia de carga queresulta en la mayor disipación de potencia es igual en valor a la resistencia de Thevenin.

**Pasos para resolver**

1.-Descubrir la resistencia de carga del circuito. Ahora retirelo del circuito.

2.-Calcule la resistencia equivalente de Thevenin del circuito desde el punto de vista de la rama de resistencia de carga en circuito abierto.

3.-Ahora como dice la teoria, la nueva resistencia de carga será la resistencia equivalente de Thevenin. Esta es la resistencia responsable de la máxima transferencia de potencia.

4.-Entonces se deriva la potencia máxima. 

**Formula**

![image](https://user-images.githubusercontent.com/105570939/184208530-6631b6ae-8946-48c7-9655-c0742c83fd4f.png)

**TEOREMA DE THEVENIN**

* Cualquier componente conectado entre estas dos terminales "Ve" efectivamente a VTH en serie con RTH. Como lo define el teorema de Thevenin.
* La resisntencia equivalente de Thevenin (RTH) es la resistencia total que aparece entre dos terminales en un circuito dado que tiene todaslas fuentes reemplazadas por sus resistencias internas.

**Pasos para resolver**

1.-Abrir las dos terminales (eliminar cualquier carga) entre las que se desea encontrar el circuito equivalente de Thevenin.

2.-Determinar el voltaje (VTH) entre las dos terminales abiertas.

3.-Determinar la resistencia (RTH) entre las dos terminales abiertas con todas las fuentes.

4.-Conectar VTH y RTH en serie para producir el equivalente de Thevenin completo del circuito original.

5.-Reemplazar la carga eliminada en el paso 1 entrelas terminales del circuito equivalente de Thevenin. Ahora se pueden calcular la corriente y el voltaje que haya en la carga utilizando solamente la ley d Ohm. Tiene el mismo valor que la corriente y el voltaje presentes en la carga del circuito original.


3. EXPLICACIÓN DEL PROCEDIMIENTO

En este punto se debe explicar cómo funcionan la implementación del circuito y los cálculos de respaldo.

Los diagramas hacen referencia a una representación visual de lo que se ha desarrollado enfocado al software y al hardware. Los diagramas son:
* Diagramas de bloques.
* Diagramas UML. (casos de uso-clase)
* Diagramas eléctricos.
* Diagramas esquemáticos.

Adicionalmente para el caso de diagramas eléctricos se debe hacer la explicación de los circuitos.

![](https://github.com/doalulema/Informe/blob/master/img/Diagrama1.jpg)

![](https://github.com/doalulema/Informe/blob/master/img/Diagrama2.jpg)

![](https://github.com/doalulema/Informe/blob/master/img/Diagrama4.jpg)


4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

En este punto se contestará todo lo planteado en las guías.

5. VIDEO

Aqui den estar el link de youtube de los videos en los que se explique el funcionamiento y la implementación del proyecto.
En el video se debe explicar 4 ejercicios o problemas.


6. CONCLUSIONES

Se estable las conclusiones de cada asunto investigado, implicaciones para la teoría y resultados de las experiencias. Estos siempre estarán en relaciona los objetivos generales y específicos.


7. BIBLIOGRAFÍA

Emplear normas APA para el informe e IEEE para el artículo


RUBRICA

![](https://github.com/doalulema/InformeLaboratorio/blob/main/Laboratorio.png)
