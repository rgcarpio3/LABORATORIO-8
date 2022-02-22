# INFORME LABORATORIO 8

## 1) Objetivos

### 1.1) Objetivo General

Analizar las ondas sinusoidales, mediante el uso de instrumentos de lectura de voltaje, para realizar el estudio dentro de circuitos eléctricos.

### 1.2) Objetivos Específicos

- Determinar el voltaje pico de una onda sinuoidal en la resistencia de carga, mediante el uso de un osciloscopio.

- Determinar el voltaje efectivo de una onda sinusoidal en la resistencia de carga, mediante el uso de un multímetr.

- Determinar la frecuaencia de la señal de salida, para obtener un mejor análisis de la onda sinusoidal.

## 2) Marco Teórico

### ONDA SINUSOIDAL

Las ondas senoidales son ondas repetitivas a través del tiempo, y sirven para describir fenómenos naturales  y señales variables en el tiempo, tal como el voltaje que distribuyen las empresas que proveen energía, y el voltaje que llega a los hogares.

Los elementos eléctricos, tales como condensadores, inductores y resistencias también producen este tipo de señales, por lo que la expresión de estas ondas en el lenguaje matemáticas está basada en las funciones seno y coseno, dependiendo de las características de cada onda. Al ser expresadas en seno y coseno, se induce que son repetitivas, es decir periódicas, en este caso, las ondas mantienen las mismas características en un intervalo de tiempo, hasta que algún factor interno o externo cambie su comportamiento.

![FIGURA 2 MARCO](https://user-images.githubusercontent.com/99141342/155038318-eb0f14c5-21d7-4ea4-b083-1bd87ccc30e6.PNG)


#### Polaridad de una onda seno

Una onda seno cambia de valores positivos a negativos o viceversa, cuando su valor llega a cero. En caso de voltaje y corriente, al alternarse de valores positivos a negativos, el voltaje y corriente cambia de sentido de circulación dentro de un circuito. Cuando se alterna una vez los valores positivos y negativos, se forma un ciclo de onda.

#### Valores de una onda senoidal

##### Valor Pico

El valor pico de una onda seno es el valor de voltaje (o corriente) en el punto máximo (pico) positivo o negativo con respecto a cero. Como los valores pico positivos y negativos son iguales en magnitud, una onda seno se caracteriza por un solo valor pico.

##### Valor Pico - Pico

El valor pico a pico de una onda seno, es el voltaje o la corriente desde el pico positivo hasta el pico negativo. Siempre es dos veces el valor pico.

##### Valor RMS

El valor rms de un voltaje sinusoidal es igual al voltaje de cd que produce la misma cantidad  de calor en una resistencia que un voltaje sinusoidal.

##### Valor Promedio

El valor promedio es el área total debajo de la curva de medio ciclo dividida entre la distancia en radianes de la curva a lo largo del eje horizontal.

![FIGURA 1 MARCO](https://user-images.githubusercontent.com/99141342/155038346-ce9e6f5e-b4d0-4c0a-84be-0633a94c0fef.PNG)

### MAPA CONCEPTUAL

![Untitled](https://user-images.githubusercontent.com/99141342/155064282-d2bc79ee-d1b7-457b-b0a8-6be76595d6dd.jpg)


## 3) Explicación del Procedimiento

1. Se arma el circuito que se presenta en la imagen

![image](https://user-images.githubusercontent.com/99141342/155038034-3dff1d2f-5fde-46e7-8ad1-145a778ee532.png)

2. Se ajusta el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 kHz

3. Se conecta el osciloscopio a la carga RL. Observar la señal que aparece en el osciloscopio

![Simulación 2](https://user-images.githubusercontent.com/99141342/155048769-4ebf3b37-8a43-47ba-b8b7-3cebe2473aa9.jpeg)



## 4) Análisis de Resultados y Respuestas a Interrogantes

Dentro de la senal generada del osciloscoío, se puede observar que el valor pico tiene un valor aproximado de 6.78V, que es el valor correspondiente cuando se aplica la ley de Ohm. Así mismo, en la lectura de del voltaje efectivo, se muestra un voltaje de 4.83 V, que es un valor menor al voltaje pico medido por el osciloscopio.

###  ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

La amplitud pico abarca un cuadro aproximándose a dos lo cual nos muestra un valor de 6,78 V

###  ¿En qué valor está posicionada la perilla VOLTS/DIV?

Se encuentra en la posición de 3

###  ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

Un ciclo completo mostrado en el osciloscopio abarca cuatro cuadros.

### ¿En qué valor está posicionada la perilla TIME/DIV?

Se encuentra en la posición de 0,1m

###  ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?

Amplitud de voltaje: 6,78 (V)

Periodo: 1/f

f = 2.5 kHz

T = 1/2.5

T = 0.4 m(s)

Periodo: 0.4 m (s)

###  Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.

f:  2500 (Hz)

ω: 2πf (rad/s) = 2π(2500) (rad/s) = 15707,96 (rad/s)

### Con el multímetro digital mida el voltaje de salida en RL: 4.86 V

![Simulación 1](https://user-images.githubusercontent.com/99141342/155048759-9b2bb902-e12c-42ff-a094-6e0a0fa5db5e.jpeg)

### Compare el voltaje medido por el osciloscopio y el voltaje medido por el multímetro

6.78 V (Osciloscopio)

4.86V (Multímetro Digital)

¿Coinciden? No ¿Por qué? Los valores del osciloscopio nos muestran el valor pico del circuito mientras que el del multímetro digital nos dicta un valor eficaz es decir Vrms. Y para ser que estos coincidan se necesita aplicar la formula:  Vrms = Vp(0.707).

## 5) Video

https://youtu.be/bg31WO6scB4

## 6) Conclusiones

- El valor pico medido en el osciloscopio indica que el voltaje se calcula mediante por la ley de Ohm, por lo que se  induce que las ondas sinusoidales también cumplen con la ley de Ohm.

- El voltaje efectivo cumple con la aplicación de la fórmula descrita, a partir del valor pico obtenido por el osciloscopio.

- La frecuencia calculada en la onda sinusoidal no influye en el valor de voltaje en la resistencia de carga.

## 7) Bibliografía

Zapata, F. (22 de Agosto de 2019). Lifeder. Obtenido de https://www.lifeder.com/onda-senoidal/

Floyd, T. (2007). Introducción a la corriente y al voltaje alternos. En LM Cruz Castillo (Ed.), Principios de Circuitos Eléctricos (VIII ed., pp. 406-465). Pearson Educación.

