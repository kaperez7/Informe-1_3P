# InformeLaboratorio


1. OBJETIVOS

Usar el Teorema de Superposición, Transferencia de Potencia y Thevenin, mediante la simulacion de los circuitos usando la herramienta tinkercad, para medir la corriente y voltaje.

* Explicar en que consisten los teoremas.
* Encontrar la corrinet y voltaje aplicando los diferentes teoremas.
* Simular los circuitos en tinkercad.


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

**TEOREMA DE MÁXIMA TRASFERENCIA DE POTENCIA**

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

**Ejercicio 1**

![image](https://user-images.githubusercontent.com/105570939/184242133-d6398aee-6005-4267-863f-ef3b207e4db4.png)

![image](https://user-images.githubusercontent.com/105570939/184246885-44105b0a-bb5c-4ee6-a6bf-1ea2b097960b.png)

![image](https://user-images.githubusercontent.com/105570939/184248008-b7700da5-fbcc-420e-88e0-1b560427b7ca.png)

**Proceso**

![image](https://user-images.githubusercontent.com/105570939/184247678-fd79dabe-6e39-4d2b-995b-e9bf64738fc9.png)

![image](https://user-images.githubusercontent.com/105570939/184247834-de963f61-c4a0-46dc-8d11-b4fcf028e58c.png)

**Ejercicio 2**

![image](https://user-images.githubusercontent.com/105570939/184248268-214b6689-b430-4e0d-bd8e-30edcdcc7d32.png)

![image](https://user-images.githubusercontent.com/105570939/184270821-305efce1-c4e6-4883-88f0-0ef4ec093e51.png)

![image](https://user-images.githubusercontent.com/105570939/184270945-41a216b6-26a8-46a9-9aee-5e7c4c3e75cd.png)

![image](https://user-images.githubusercontent.com/105570939/184271021-71fc6e1d-9528-4a44-b7ca-6f0d94f23bc8.png)

**Aplicando Thevenin**

![image](https://user-images.githubusercontent.com/105570939/184271621-cd78e03f-8531-4a32-b5f5-32d386aba3df.png)

![image](https://user-images.githubusercontent.com/105570939/184272108-c5afee45-6942-45fb-b51c-4eedf9de193a.png)

**Ejercicio 3**

![image](https://user-images.githubusercontent.com/105570939/184273687-352ab176-3f90-4f80-93ee-99efc3e7a135.png)

![image](https://user-images.githubusercontent.com/105570939/184273853-cbd1ba10-2900-437b-93b4-8533e64df643.png)

![image](https://user-images.githubusercontent.com/105570939/184274314-0efec8ce-e96c-4be8-bc41-a1f28ced076e.png)


**Aplicando Thevenin**

![image](https://user-images.githubusercontent.com/105570939/184272533-0837050f-ecee-4605-8bc6-80980d507ddc.png)

![image](https://user-images.githubusercontent.com/105570939/184272554-89663db4-d80e-44e4-90cf-179be7348e24.png)

4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

**Ejercicio1**

I=500-400       I=100mA

**Ejercicio2**

VTH=8.32 V           RTH=4.7KΩ

P=IxV     P=3.78x8.32     P=31.44mW

**Ejercicio 3**

VTH=10 V    RTH=5Ω

I=909 mA

5. VIDEO

Aqui den estar el link de youtube de los videos en los que se explique el funcionamiento y la implementación del proyecto.
En el video se debe explicar 4 ejercicios o problemas.


6. CONCLUSIONES

* EL teorema de la Máxima Transferencia de Potencia consiste en demostrar que al implementar en un circuito una resistencia con el mismo o semejante valor a la resistencia de la fuente la potencia alcanza su máximo valor.
* Si aplicamos el teorema de Superposición es necesario tener en cuenta que las fuentes de voltaje al igualarlas a 0 se comportan como un cortocircuito, por otro lado si tuvieramos fuentes de corriente estas se van a comportar como circuitos abiertos.
* Simulando los circuitos en tinkercad se pudo encontrar la corriente y el voltaje de los circuitos planteados en los ejercicios.


7. BIBLIOGRAFÍA

Teorema de transferencia de potencia máxima. (s. f.). Iustrationprize. Recuperado 12 de julio de 2022, de https://illustrationprize.com/es/22-maximum-power-transfer-theorem.html

Superposición (artículo). (s. f.). Khan Academy. Recuperado 28 de junio de 2022, de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-superposition

Teorema de Thevenin - Explicado con ejercicios resueltos. (2021, 23 enero). Mi Universo Electrónico. Recuperado 5 de julio de 2022, de https://miuniversoelectronico.com/el-teorema-de-thevenin/

RUBRICA

![](https://github.com/doalulema/InformeLaboratorio/blob/main/Laboratorio.png)
