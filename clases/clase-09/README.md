# clase-09

martes 11 octubre 2022, presencial

## repaso clase anterior y programa hoy

la clase anterior vimos la unidad 5: calor y temperatura

- gases ideales
- unidades de medida en gases ideales
- condiciones estándar en gases ideales
- calor
- transferencia de calor
- leyes de la termodinámica
- temperatura
- expansión térmica

la clase de hoy es la unidad 6: ondas y sonido

- definición de onda
- definición de sonido

## definición de onda

cuando grafiquemos ondas, vamos a tener 2 gráficos:

- gráfico de amplitud de la onda en el tiempo, lo que implica que el punto en el espacio está fijo,
  aquí el eje horizontal de la variable independiente es TIEMPO.

- gráfico de amplitud de la onda en el espacio, lo que implica que el tiempo está fijo o detenido,
  aquí el eje horizontal de la variable independiente es ESPACIO.

ojo con los ejes!!

## longitud de onda

la longitud de onda es la distancia entre repeticiones de la onda.

la longitud de onda es una distancia y se mide en metros.

la longitud de onda se simboliza con la letra griega lambda.

$$\lambda$$

- amplitud: distancia entre el punto de equilibrio y el desplazamiento máximo, medida en metros.
- periodo: tiempo que demora
- frecuencia: inverso del periodo, se mide en Hz.

la amplitud de una onda es la .

## definición de sonido

el sonido es una producida por un cuerpo en vibración.

la vibración comprime y descomprime el aire alrededor, lo que genera una onda longitudinal.

las moléculas de aire oscilan de forma paralela a la dirección del movimiento de la onda, recibiendo energía de moléculas adyacentes.

## relaciones entre mundo físico y perceptual

la amplitud de una onda de sonido la percibimos como volumen.

la frecuencia del sonido la percibimos como altura.

## percepción logarítmica de volumen

nuestra percepción es logarítmica en cuanto a volumen.

## velocidad del sonido

a 20 Celsius, la velocidad del sonido es de 343 metros por segundo, y es la velocidad que usaremos en este curso.

$$v_{sonido} = 343 \cdot \frac{m}{s}$$

como sabemos que la velocidad de una onda

$$v_{sonido} = \lambda \cdot f_{sonido}$$

entonces podemos calcular la longitud de onda de cualquier onda si sabemos su frecuencia.

por ejemplo, la longitud de una onda 20 Hz:

$$\lambda_{20Hz} = \frac{v_{sonido}}{f_{sonido}} = \frac{343 \cdot \frac{m}{s}}{20 Hz} = 17.15 \cdot m$$

por ejemplo, la longitud de una onda de 20 kHz

$$\lambda_{20kHz} = \frac{v_{sonido}}{f_{sonido}} = \frac{343 \cdot \frac{m}{s}}{20k Hz} = 17.15 \cdot mm$$

entonces otra forma de pensar en el rango humano de escucha, en vez de pensar en frecuencias, podemos también pensar en longitudes de onda mínima y máxima.

## análisis de Fourier

Fourier postuló que toda onda se puede expresar como una suma de ondas sinusoidales.

esto es genial, porque las sinusoides se identifican con 3 datos:

1. amplitud
2. frecuencia
3. fase

entonces, si tenemos una máquina que es capaz de crear ondas sinusoidales y sumarlas, podemos crear cualquier onda, por ejemplo, el sonido.

por eso, en ciencias tendemos a analizar las señales y ondas en función de las sinusoides que los conforman.

un típico nombre que encuentran en computación es FFT, que significa Fast Fourier Transform.

## primer paso para digitalizar: muestrear

para grabar un sonido y pasarlo de una señal analógica a una digital, tenemos que muestrear el sonido, pasar de una onda que tiene un valor en todo momento, a tener muestras que sean muy representativas en el tiempo.

para esto elegimos una frecuencia de muestreo, que significa cuán seguido tomamos una muestra.

## bibliografía

- https://www.cliffsnotes.com/study-guides/physics/waves-and-sound/wave-motion
- https://www.cliffsnotes.com/study-guides/physics/waves-and-sound/sound
- https://en.wikipedia.org/wiki/Wavelength
