# ayudantia-11

jueves 27 octubre 2022, presencial

## ejercicio-01: espectro de luz visible (30 min)

a) si el color violeta lo definimos con longitud de onda entre 380 nm y 435 nm, encontrar las frecuencias equivalentes.

b) si una onda de color rojo con longitud de onda entre 625 nm y 750 nm viaja 3 años luz, cuántas veces oscila la onda en este trayecto?

## solución ejercicio-01

a)

la velocidad de la luz se denota por la letra c minúscula, y tiene el valor de 300 mil kilómetros por segundo.

$$c = 3 \cdot 10^8 \cdot \frac{m}{s}$$

sabemos que la velocidad de la luz es una constante, y que para toda onda, es igual al producto de la longitud de onda por la frecuencia de la onda.

$$c = \lambda \cdot f$$

la longitud de onda y la frecuencia son inversamente proporcionales, entonces la longitud de onda máxima define la frecuencia mínima, y viceversa.

entonces reemplazando:

$$3 \cdot 10^{8} \cdot \frac{m}{s} = 380 \cdot 10^{-9} m \cdot f_{max}$$

multiplicamos a ambos lados por 10 elevado a 9:

$$3 \cdot 10^{17} \cdot Hz = 380 \cdot f_{max}$$

dividimos por 380:

$$f_{max} = \frac{3}{380} \cdot 10^{17} \cdot Hz$$

veamos ahora la frecuencia mínima:

$$3 \cdot 10^{8} \cdot \frac{m}{s} = 435 \cdot 10^{-9} m \cdot f_{min}$$

despejando:

$$f_{min} = \frac{3}{435} \cdot 10^{17} \cdot Hz$$

entonces la respuesta es que las frecuencias del color violeta están entre los valores mínimos y máximos calculados.

b)

sabemos que la velocidad de la luz es igual a la longitud de onda multiplicada por su frecuencia, entonces:

$$c = 3 \cdot 10^{8} \frac{m}{s} = \lambda \cdot f$$

veamos la frecuencia mínima, asociada a la longitud de onda máxima:

$$3 \cdot 10^{8} \cdot \frac{m}{s} = \lambda_{max} \cdot f_{min}$$

y despejando f_min:

$$f_{min} = \frac{3 \cdot 10^{8} \cdot \frac{m}{s}}{750 \cdot nm}$$

simplificando:

$$f_{min} = \frac{3 \cdot 10^{8}}{750 \cdot 10^{-9}} \cdot Hz$$

$$f_{min} = \frac{3}{750} \cdot 10^{17} \cdot Hz$$

veamos ahora la frecuencia máxima, asociada a la longitd de onda mínima:

$$3 \cdot 10^{8} \cdot \frac{m}{s} = \lambda_{min} \cdot f_{max}$$

y despejando f_max:

$$f_{max} = \frac{3 \cdot 10^{8} \cdot \frac{m}{s}}{625 \cdot nm}$$

simplificando:

$$f_{max} = \frac{3 \cdot 10^{8}}{625 \cdot 10^{-9}} \cdot Hz$$

$$f_{max} = \frac{3}{625} \cdot 10^{17} \cdot Hz$$

las frecuencias mínimas y máximas nos dan el rango de cuántas oscilaciones completa esta onda en un segundo.

ahora queremos ver cuántas oscilaciones ocurren mientras recorre una distancia de 3 años luz, y como es luz, la velocidad es la velocidad de la luz y se demora 3 años.

entonces basta con multiplicar las frecuencias por la cantidad de tiempo de 3 años para encontrar el rango de oscilaciones.

$$oscilaciones_{min} = f_{min} \cdot 3 \cdot años = \frac{3}{750} \cdot 10^{17} \cdot Hz \cdot 365.25 \cdot 24 \cdot 60 \cdot 60 segundos$$

y podemos simplificar Hz con segundos, resultando en el número

$$oscilaciones_{min} = \frac{3}{750} \cdot 365.25 \cdot 24 \cdot 3600 \cdot 10^{17}$$

y aproximadamante:

$$oscilaciones_{min} = \approx 126230 \cdot 10^{17}$$

veamos ahora las oscilaciones máximas

$$oscilaciones_{max} = f_{max} \cdot 3 \cdot años = \frac{3}{625} \cdot 10^{17} \cdot Hz \cdot 365.25 \cdot 24 \cdot 60 \cdot 60 segundos$$

y podemos simplificar Hz con segundos, resultando en el número

$$oscilaciones_{max} = \frac{3}{625} \cdot 365.25 \cdot 24 \cdot 3600 \cdot 10^{17}$$

y aproximadamante:

$$oscilaciones_{max} = \frac{3}{625} \cdot 365.25 \cdot 24 \cdot 3600 \cdot 10^{17} $$

$$oscilaciones_{min} = \approx 151476  \cdot 10^{17}$$

## ejercicio-02: información en imágenes (30 min)

a) cuántos colores posibles puede tener un pixel RGB de 4 bits por canal?

b) cuántas imágenes posibles puede tener una pantalla de 10 pixeles de alto por 20 pixeles de ancho, usando el sistema anterior?

## solución ejercicio-02

a)

si tenemos 4 bits por canal, y tenemos 3 canales de color (R, G y B), entonces tenemos 12 bits de información en un pixel.

por cada pixel, tenemos 2 posibles estados: 0 y 1.

la cantidad de colores posibles con B bits está dada por 2 elevado a B, así que en este caso.

$$colores = 2^{B} = 2^{12} = 4096$$

con este sistema, cada pixel puede expresar 4096 colores diferentes.

b)

ya sabemos que cada pixel tiene 12 bits de información.

calculemos ahora el número de pixeles en la pantalla, multiplicando el número de pixeles de ancho por el de alto.

$$pixeles = 10 \cdot 20 = 200$$

entonces, tenemos 200 pixeles, y la información por pixel es 12 bits, entonces si los multiplicamos, tenemos el total de bits necesarios para definir todos los pixeles de la pantalla.

$$bits = 200 \cdot pixeles \cdot 12 \cdot \frac{bits}{pixel} = 2400 \cdot bits$$

entonces en toda la pantalla, tenemos 2400 bits de información.

la cantidad de imágenes posibles que podemos formar con estos bits es 2 elevado al número de bits.

$$imágenes = 2^{B} = 2^{2400} \approx 3 \cdot 10^{722} $$

con esta pequeña pantalla, de baja resolución, la cantidad de imágenes posibles es enorme!

## ejercicio-03: información en video (30 min)

a) cuánta información, medida en bits, hay en una transmisión de:

- 1.2 minutos de duración
- 30 cuadros por segundo
- resolución de 1280 x 720 pixeles por cuadro
- colores RGB de 8 bits por color

b) cuánta es la duración máxima de un video con las mismas características que el video anterior, que cabe en un disco duro de 1 TB?

dato:

$$1 \cdot TB = 10^{12} \cdot bytes = 8 \cdot 10^{12} \cdot bits$$

## solución ejercicio-03

a)

primero encontremos cuántos bits hay en cada pixel

$$\frac{bits}{pixel} = \frac{bits_{R} + bits_{G} + bits_{B}}{pixel} =  \frac{3 \cdot (8 \cdot bits)}{pixel} = 24 \frac{bits}{pixel}$$

ahora podemos multiplicar la cantidad de bits/pixel por la resolución de pixeles/cuadro, para encontrar cuántos bits hay en 1 cuadro.

$$\frac{bits}{cuadro} = \frac{bits}{pixel} \cdot \frac{pixel}{cuadro}$$

y reemplazando los valores:

$$\frac{bits}{cuadro} = 24 \cdot \frac{bits}{pixel} \cdot (1280 \cdot 720)\frac{pixel}{cuadro}$$

y simplificando:

$$\frac{bits}{cuadro} = 24 \cdot 1280 \cdot 720 \cdot \frac{bits}{cuadro} = 22,118,400 \cdot \frac{bits}{cuadro}$$

ahora tenemos la cantidad de bits/cuadro, si multiplicamos por la cantidad de cuadros/segundo, tendremos la cantidad de bits/segundo:

$$\frac{bits}{segundo} = \frac{bits}{cuadro} \cdot \frac{cuadros}{segundo}$$

y reemplazando los valores:

$$\frac{bits}{segundo} = 22,118,400 \cdot \frac{bits}{cuadro} \cdot 30 \cdot \frac{cuadros}{segundo}$$

y simplificando:

$$\frac{bits}{segundo} = 663,552,000 \cdot \frac{bits}{segundo}$$

ahora tenemos la cantidad de bits que este video necesita por cada segundo, si multiplicamos por la cantidad de tiempo que dura este video, tendremos la cantidad total de bits

$$ bits = \frac{bits}{segundo} \cdot segundos$$

y reemplazando los valores:

$$bits = 663,552,000 \cdot \frac{bits}{segundo} \cdot 1.2 minutos =  663,552,000 \cdot \frac{bits}{segundo} \cdot 1.2 \cdot 60 \cdot segundos$$

y simplificando:

$$bits = 663,552,000 \cdot 1.2 \cdot 60 \cdot bits = 47,775,744,000 \cdot bits \approx 48 \cdot 10^{9} \cdot bits$$

b)

en el ejercicio anterior vimos que la tasa de bits necesarias por segundo era igual a:

$$\frac{bits}{segundo} = 663,552,000 \cdot \frac{bits}{segundo}$$

y tenemos que el disco duro tiene una capacidad de 1 TB, que en palabras, es un tera byte.

$$disco = 1 \cdot TB = 1 \cdot 10^8 \cdot byte = 8 \cdot 10^8 \cdot bits$$

si tomamos la capacidad del disco y la dividimos por la tasa de bits por segundo del video, encontraremos la duración máxima:

$$duracion = \frac{capacidad}{tasa}$$

y reemplazando los valores:

$$duracion = \frac{8 \cdot 10^{12} \cdot bits}{663,552,000 \cdot \frac{bits}{segundo}}$$

y simplificando las unidades:

$$duracion = \frac{8 \cdot 10^{12}}{663,552,000} \cdot segundos$$

y simplificando las potencias de 10:

$$duracion = \frac{8 \cdot 10^9}{663,552} \cdot segundos = \frac{1953125}{162} \cdot segundos$$

y luego aproximando:

$$duracion = \frac{1953125}{162} \cdot segundos \approx 12056 \cdot segundos \approx 201 minutos$$

la duración aproximada que cabe en un disco duro de 1 TB de esta resolución es 201 minutos.
