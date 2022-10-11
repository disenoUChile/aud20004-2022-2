# ayudantia-09

## ejercicio-01

a)

b)

## solución ejercicio-01

a)

b)

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

## ejercicio-03: velocidad del sonido (30 min)

a) si en un cierto material, una onda con un periodo de 5 segundos, tiene una longitud de onda de 1 kilómetro, cuál es la velocidad del sonido en ese material? en ese mismo material, cuál es la longitud de una onda de 1 kHz?

a) si vemos un trueno y lo escuchamos 12 segundos después, a qué distancia está? cuán cerca tenemos que estar de una fuente sonora para tener un retraso menor a 1 ms?

## solución ejercicio-03

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
