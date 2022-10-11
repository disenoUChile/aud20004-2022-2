# ayudantia-09

## ejercicio-01: velocidad del sonido (30 min)

a) si en un cierto material, una onda con un periodo de 5 segundos, tiene una longitud de onda de 1 kilómetro, cuál es la velocidad del sonido en ese material? en ese mismo material, cuál es la longitud de una onda de 1 kHz?

a) si vemos un trueno y lo escuchamos 12 segundos después, a qué distancia está? cuán cerca tenemos que estar de una fuente sonora para tener un retraso menor a 1 ms?

## solución ejercicio-01

a)

en estos ejercicios, usaremos la fórmula que relaciona velocidad del sonido en un material, con su longitud de onda y con su frecuencia.

$$velocidad_{sonido} = \lambda \cdot frecuencia$$

para una onda con periodo 5 segundos, tenemos que su frecuencia es:

$$f_1 = \frac{1}{T_1} = \frac{1}{5 s} = 0.2 Hz$$

entonces la velocidad del sonido en este material es:

$$v_{sonido} = \lambda_{1} \cdot f_1 = 1 km \cdot 0.2 Hz = 200 \cdot \frac{m}{s}$$

en este mismo material, si tenemos una onda con otra frecuencia, podemos partir de la misma ecuación

$$v_sonido = \lambda_{2} \cdot f_2$$

y despejar la longitud de onda así:

$$\lambda_{2} = \frac{v_sonido}{f_2} = \frac{200 \frac{m}{s}}{ 1 \cdot kHz}$$

y como por definición 1/s es Hz, podemos simplificarlos y seguir:

$$\lambda_{2} = 200 \cdot mm$$

b)

para encontrar la distancia del trueno, multiplicamos la velocidad del sonido por el tiempo transcurrido, y con eso podemos encontrar la distancia pedida.

$$distancia_{trueno} = velocidad_{sonido} \cdot tiempo$$

reemplazando los valores:

$$distancia_{trueno} = 343 \cdot \frac{m}{s} \cdot 12 \cdot s = 4116 m$$

si queremos tener un retraso menor a 1 ms, esto lo podemos plantear con la siguiente ecuación:

$$distancia_{pedida} = velocidad_{sonido} \cdot tiempo_{pedido}$$

si reemplazamos tiempo con 1 ms, tenemos que la distancia es:

$$distancia_{pedida} = 343 \cdot \frac{m}{s} \cdot 1 \cdot ms = 343 mm$$

entonces, tenemos que estar a menos de 343 mm de distancia de la fuente sonora, para un retraso menor a 1 ms.

## ejercicio-02: efecto Doppler (30 min)

a) si fuente de sonido emite una frecuencia de 2 kHz y se mueve a una velocidad de 30 km/h hacia ti que estás con velocidad 0 km/h, qué frecuencia escuchas cuándo se acerca? y cuando se aleja?

b) si una fuente de sonido emite una frecuencia de 3 kHz, a qué velocidad debe moverse hacia ti con respecto a ti que estás con velocidad 0 km/h, para que cuando se acerque escuches el doble de esa frecuencia?

## solución ejercicio-02

a)

primero convirtamos la velocidad de 30 km/h de la fuente de sonido a metros / segundo.

$$v_{fuente} = 30 \cdot \frac{km}{h} = 30 \cdot \frac{1000 \cdot m}{60 \cdot 60 \cdot s} = \frac{300}{36} \cdot \frac{m}{s} = \frac{25}{3} \cdot \frac{m}{s} \approx 8 \cdot \frac{m}{s}$$

la ecuación para el efecto Doppler es:

$$f = f_{original} \cdot \frac{v_{sonido} \mp v_{receptor}}{v_{sonido} \mp v_{fuente}}$$

en este caso, la velocidad del receptor es 0 y podemos simplificar la ecuación a:

$$f = f_{original} \cdot \frac{v_{sonido}}{v_{sonido} \mp v_{fuente}}$$

y reemplazando los valores:

$$f = 2 \cdot kHz \cdot \frac{343 \frac{m}{s}}{343 \cdot \frac{m}{s} \mp 8 \cdot \frac{m}{s}} = 2 \cdot kHz \cdot \frac{343}{343 \mp 8}$$

cuando la fuente de sonido se acerca hacia ti, la frecuencia aumenta, por lo que:

$$f_{acerca} = 2 \cdot kHz \cdot \frac{343}{343 - 8} = 2 \cdot kHz \cdot \frac{343}{335} = 2047.76 Hz$$

cuando la fuente de sonido se aleja de ti, la frecuencia disminuye, por lo que:

$$f_{aleja} = 2 \cdot kHz \cdot \frac{343}{343 + 8} = 2 \cdot kHz \cdot \frac{343}{351} = 1954.42 Hz$$

b)

la ecuación para el efecto Doppler es:

$$f = f_{original} \cdot \frac{v_{sonido} \mp v_{receptor}}{v_{sonido} \mp v_{fuente}}$$

nuestra velocidad es 0 km/h, así que podemos reemplazar:

$$f = f_{original} \cdot \frac{v_{sonido}}{v_{sonido} \mp v_{fuente}}$$

reemplacemos las frecuencias, la original es 3 kHz, y queremos que la percibida sea el doble, 6 kHz.

$$6 \cdot kHz = 3 \cdot kHz \cdot \frac{v_{sonido}}{v_{sonido} \mp v_{fuente}}$$

si dividimos a ambos lados por 3 kHz, simplificamos

$$2 = \frac{v_{sonido}}{v_{sonido} \mp v_{fuente}}$$

como el sonido viene hacia ti, la frecuencia aumenta, por lo que el signo positivo o negativo del denominador es negativo.

$$2 = \frac{v_{sonido}}{v_{sonido} - v_{fuente}}$$

multiplicamos por el denominador

$$2 \cdot v_{sonido} - 2 \cdot v_{fuente} = v_{sonido}$$

y si restamos la velocidad del sonido a ambos lados

$$v_{sonido} - 2 \cdot v_{fuente} = 0$$

y con esto despejamos la velocidad de la fuente

$$v_{fuente} = \frac{1}{2} \cdot v_{sonido}$$

y reemplazando el valor de la velocidad del sonido

$$v_{fuente} = \frac{1}{2} \cdot 343 \frac{m}{s} = 171.5 \frac{m}{s}$$

## ejercicio-03: digitalización de ondas

a) si queremos digitalizar ondas hasta 30 kHz, cuál es la frecuencia de muestreo que debemos usar? si el audio digital de calidad CD tiene una frecuencia de muestreo de 44.1 kHz, cuál es el rango de frecuencia que puede capturar?

b) si tenemos un audio donde la resolución de cada muestra tiene 8 bits, cuántos posibles valores existen? si el audio digital tiene valores entre -1 y 1, cuánto mide la distancia entre estados? y cómo se diferencia esto con una resolución de 16 bits?

## solución ejercicio-03

a)

según el teorema de Nyquist, debemos muestrear a estrictamente más del doble de la frecuencia máxima, según la ecuación

$$f_{muestreo} > 2 \cdot f_{maxima}$$

y reemplazando los valores

$$f_{muestreo} > 2 \cdot 30 kHz$$

llegamos al resultado

$$f_{muestreo} > 60 kHz$$

entonces la frecuencia de muestreo debe ser mayor a 60 kHz.

para el caso de la calidad de CD, si la frecuencia de muestreo es de 44.1 kHz, podemos usar el teorema de Nyquist

$$f_{muestreo} > 2 \cdot f_{maxima}$$

y reemplazar la frecuencia de muestreo para encontrar la frecuencia máxima

$$44.1 kHz > 2 \cdot f_{maxima}$$

y diviendo por dos a ambos lados

$$22.05 kHz > f_{maxima}$$

con lo que sabemos ahora que la frecuencia máxima en calidad CD es menor a 22.05 kHz.

b)

- con 1 bit, tenemos 2 estados posibles: 0, 1.
- con 2 bits, tenemos 4 estados posibles: 00, 01, 10, 11.
- con 3 bits, tenemos 8 estados posibles: 000, 001, 010, 011, 100, 101, 110, 111.

con cada bit adicional, tenemos el doble de estados posibles, entonces la fórmula que relaciona números de bits B con estados posibles es:

$$estados = 2^B$$

entonces con 8 bits tenemos que el número de estados posibles es

$$estados = 2^{B} = 2^8 = 256$$

estos 256 valores posibles tienen que cubrir el rango entre -1 y 1, que mide 2.

entonces cada paso mide:

$$paso = \frac{rango}{pasos} =  \frac{2}{256} \approx 0.0078$$

veamos ahora con 16 bits.

el número de estados con 16 bits es mucho mayor:

$$estados = 2^{B} = 2^{16} = (2^8)^2 = 65536$$

y con esto, el paso entre cada estado posible es mucho menor.

$$paso = \frac{rango}{pasos} = \frac{2}{655356} \approx 0.0000305$$
