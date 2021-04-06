# Laboratorio9
## Amplificador operacional
### 1.	OBJETIVOS

**Principales**

 - Experimentar los amplificadores Operacionales

**Específicos**

- Explicar la teoria de amplificadores operacionales
- Familiarizarse con el uso de amplificadores operacionales
- Testar el circuito con el amplificador operacional

### 2.	MARCO TEÓRICO 

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/1.png)

### 3.	DIAGRAMAS

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/2.png)

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/3.png)

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/4.png)


### 4.	LISTA DE COMPONENTES

| Cantidad | Componentes | 
| -------- | ----------- |
| 2 | Generador de señales |
| 2 | Fuente DC |
| 1 | Osciloscopio | 
| 1 | Protoboard | 
| 1 | Multimetro |
| 1 | Resistencia 300 Ω | 
| 1 | Resistor de 200 Ω |
| 1 | Resistor de 4,3 kΩ | 
| 1 | Resistor de 1 kΩ | 
| 1 | Capacitor de 1 uF | 
| 1 | Resistor de 1 kΩ |
| 1 | Amplificador operacional LM741 | 
 

 
> (Herramientas utilizadas en simulación) 
> Simulador Tinkercad


### 5.	EXPLICACIÓN

5.5.1. Analice y compare las formas de onda obtenidas en la práctica con los resultados obtenidos
en el trabajo preparatorio. Comente dicha comparación.

#### Análisis Circuito 1

En la señal de entrada se observa que es unseñal senoidal la cual nos indica la señal que es un seno con una frecuencua de 3k Hz. Podemos ocbervar quee en la señal de salida conectando el osciloscopio nos da una señal lineal esto depende del las divisiones que tiene el osciloscopio en este caso la segunda señal que semuestra sus divisiones de 100 us ya que se podria observar mucho mejor a la señal si se pudiera acercar, es un amplificador de ganacia en 1 inversor este circuito. 

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/5.png)

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/6.png)

#### Análisis Circuito 2

La señal de entrada que observamos es una señal cuadrada ya que tenemos una frecuencia de 3k Hz con 5V al conectar el osciloscopio vemos que el tiempo por división es 100 us y en la señal de salida al conectar el osciloscopio el tiempo por división es de 1000 us se puede observar acercándolo que se parece a una señal triangular como me muestra   y este amplificador es un amplificador integrador el cual debe darme una señal triangular 

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/5.png)

Tiempo de división de entrada

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/5.png)

Tiempo de división de salida 

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/5.png)

#### Análisis Circuito 3

Tenemos un amplificador sumador inversor por lo que tenemos 2 fuentes ac ambas tienes la misma frecuencia de 3kHz las cuales se van a sumar y entrar al amplificador 741 se observa que la señal de entrada es una señal senoidal con el tiempo por división de 1000 us y se muestra la señal mientras que en la señal de salida en el osciloscopio se muestra una señal mas pequeña con las mismas divisiones.

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/5.png)

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/5.png)

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/5.png)

#### PREGUNTAS

5.5.2. Anote parámetros técnicos importantes de un amplificador operacional que deben ser
tomados en cuenta al momento de utilizarlos en un proyecto.

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/5.png)

Este es un esquema que se debe tener en cuenta a la hora de realizar un circuito, pues de esta forma podemos observar el modo de conexión y la cantidad de conexiones en el circuito.
También debemos considerar la entrada con 2 cuyos signos son (+) y (-), que son inversoras y no inversoras y de salida.
También debe tenerse en cuenta que la entrada aplicada al terminal no inversor aparecerá con la misma polaridad en el terminal de salida, mientras que la entrada aplicada al terminal inversor aparecerá invertida en el terminal de salida.

5.5.3. Investigue las características de amplificadores operacionales distintos a los utilizados en
esta práctica.

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio9/blob/main/Fotos/5.png)

La parte de salida está compuesta por una fuente de alimentación controlada por voltaje conectada en serie con la resistencia de salida Ro. Es obvio que la resistencia de entrada Ri es la resistencia equivalente de Thévenin vista en el terminal de entrada, y la resistencia de salida Ro es la resistencia equivalente de Thévenin vista en el terminal de salida. El voltaje de entrada diferencial vd viene dado por:

Vd=V2-V1

Entre ellos, v1 es el voltaje entre el terminal inversor y tierra, y v2 es el voltaje entre el terminal no inversor y tierra. El amplificador operacional puede detectar la diferencia entre estas dos entradas, luego multiplicarla por la ganancia A y hacer que el voltaje resultante aparezca en la salida. Por tanto, la salida vo viene dada por:

vo = Avo = A(v2 - v1)

A se denomina ganancia de voltaje de bucle abierto porque es la ganancia de un amplificador operacional y no hay retroalimentación externa de salida a entrada.

5.5.4. Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores
operacionales.






### 6.	 DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

 
- Crear un usaurio en tinkercad
- Tener listo la opcion de diagrama de circuito
 
### 7.	APORTACIONES

 - Cambia la corriente de una malla al agregar o quitar resstencias
 - No es lo mismo la medición de voltaje con corriente 
 - El multímetro tiene diferentes funcionamientos dependiendo si es digital o análogo.
 - La fuente de corriente directa mide cuantos amperios tiene el circuito.
 
### 8.	CONCLUSIONES

 - La teoria de thevenin si se aplica en las propiedades de su uso en la vida real
 - Al tener especificado en la teroía los resultados, sis se tiene un resultado con un menor error, pero eso no se reflejaria en la vida real, debido a que no existe circuitos perefctos a temperatura ambiente.
 - La teroia de thevenin si es correcta al poder simlifcar los caculosn y con ello que se pueda ahorrar mas materiales en un caso de que se construya un circuito.

### 9.	BIBLIOGRAFÍA

[1] Floyd, T. (2007). Principios de circuitos electricos. Mexico: Pearson Educacion. Serway,


### 10.	 ANEXOS


