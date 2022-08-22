# ayudantia-03

## ejercicio-01 (30 min)

a) si tenemos la ecuación de velocidad de un cuerpo es:

$$v(t) = v_{0} + a \cdot t$$

y si sabemos los siguientes valores de velocidad en ciertos instantes:

- $v(t=5s) = 4 \frac{m}{s}$
- $v(t=7s) = 10 \frac{m}{s}$

encontrar los valores de $v_{0}$ y $a$ para definir la ecuación.

b) si tenemos otro cuerpo con la ecuación de velocidad

$$v(t) = 5 \frac{m}{s} -3 \frac{m}{s^{2}} \cdot t$$

encontrar el instante $t_{\*}$ en que tienen la misma velocidad $v_{\*}$.

## solución ejercicio-01

a)

sabemos que para $t_1$ y $t_2$, podemos escribir el sistema

$$v_{1} = v_{0} + a \cdot t_1 \brack v_{2} = v_{0} + a \cdot t_2$$

si restamos la primera ecuación de la segunda, obtenemos:

$$v_{1} - v{2} = a \cdot (t_{1} - t_{2})$$

y con esto podemos despejar la aceleración:

$$a = \frac{v_{1} - v_{2}}{t_{1} - t{2}}$$

y reemplazando con nuestros datos, obtenemos:

$$a = \frac{4 \frac{m}{s} - 10 \frac{m}{s}}{5s - 7s} = \frac{-6}{-2} \cdot \frac{m}{s^{2}} = 3 \frac{m}{s^{2}}$$

ahora solamente nos falta obtener $v_{0}$, por lo que partiendo de la ecuación de velocidad:

$$v(t) = v_{0} + a \cdot t$$

y reemplazando con la información que tenemos sobre el primer instante $t=5s$:

$$4 \frac{m}{s} = v_{0} + 3 \frac{m}{s^{2}} \cdot 5s$$

despejando $v_{0}$:

$$v_{0} = 4 \frac{m}{s} - 3 \cdot 5 \frac{m \cdot s}{s^{2}}$$

simplificando:

$$v_{0} = 4 \frac{m}{s} - 15 \frac{m}{s} = -11 \frac{m}{s}$$

para verificar que nuestro resultado de $v_0$ está correcto, podemos usar el otro instante y comprobar que llegamos al mismo resultado de $v_0$, veamos:

$$v(t) = v_{0} + a \cdot t$$

$$10 \frac{m}{s}= v_{0} + 3 \frac{m}{s^{2}} \cdot 7s$$

$$v_{0} =  10 \frac{m}{s} - 3 \cdot 7 \frac{m \cdot s}{s^{2}}  $$

$$v_{0} =  10 \frac{m}{s}  - 21 \frac{m}{s}$$

$$v_{0} =  -11 \frac{m}{s}$$

el mismo resultado!

podemos decir entonces que la ecuación de velocidad es:

$$v(t) = -11 \frac{m}{s} + 3 \frac{m}{s^{2}} \cdot t$$

b)

ahora tenemos este sistema de ecuaciones, donde queremos encontrar en qué instante $t_{\*}$ los dos cuerpos tienen la misma velocidad $v_{\*}$.

$$v(t) = -11 \frac{m}{s} + 3 \frac{m}{s^{2}} \cdot t \brack v(t) = 5 \frac{m}{s} -3 \frac{m}{s^{2}} \cdot t$$

cuando las velocidades son iguales, podemos igualar los lados derechos de las ecuaciones, resultando en:

$$ -11 \frac{m}{s} + 3 \frac{m}{s^{2}} \cdot t = 5 \frac{m}{s} -3 \frac{m}{s^{2}} \cdot t$$

sumamos $3 \frac{m}{s^{2}} \cdot t$ a ambos lados:

$$ -11 \frac{m}{s} + 6 \frac{m}{s^{2}} \cdot t = 5 \frac{m}{s} $$

sumamos $-11 \frac{m}{s}$ a ambos lados:

$$ 6 \frac{m}{s^{2}} \cdot t = 16 \frac{m}{s} $$

dividimos por $\frac{m}{s}$

$$ 6 \frac{1}{s} \cdot t = 16 $$

dividimos por $6$ y multiplicamos por $s$:

$$t = \frac{16}{6} s = \frac{8}{3} s \approx 2.66 s$$

para encontrar ahora la velocidad, basta con reemplazar ese instante en cualquiera de las ecuaciones y el resultado de la velocidad será el mismo.

$$v(t=\frac{8}{3} s) = -11 \frac{m}{s} + 3 \frac{m}{s^{2}} \cdot \frac{8}{3} s$$

y despejando:

$$v(t=\frac{8}{3} s) = -11 \frac{m}{s} + \frac{m}{s} \cdot 8  = -3 \frac{m}{s}$$

para verificar que el resultado es correcto, reemplacemos el tiempo en la otra ecuación de velocidad:

$$v(t=\frac{8}{3} s) = 5 \frac{m}{s} - 3 \frac{m}{s^{2}} \cdot \frac{8}{3} s = 5 \frac{m}{s} - 8 \frac{m}{s} = -3 \frac{m}{s}$$

con esto, tenemos que la respuesta que las velocidades serán iguales, su valor será $-3 \frac{m}{s}$ y esto ocurrirá en el instante $\frac{8}{3} s$.

## ejercicio-02 (30 min)

veamos ahora en 2 dimensiones, de forma vectorial

## ejercicio-03 (30 min)
