# ayudantia-03

## ejercicio-01 (30 min)

a) si tenemos la ecuación de velocidad de un cuerpo es:

$$v(t) = v_{0} + a \cdot t$$

y si sabemos los siguientes valores de velocidad en ciertos instantes:

- $v(t=5s) = 4 \frac{m}{s}$
- $v(t=7s) = 10 \frac{m}{s}$

encontrar los valores de velocidad inicial y aceleración para definir la ecuación.

b) si tenemos otro cuerpo con la ecuación de velocidad

$$v(t) = 5 \frac{m}{s} -3 \frac{m}{s^{2}} \cdot t$$

encontrar el instante en que tienen la misma velocidad.

## solución ejercicio-01

a)

sabemos que para por definición, la aceleración es:

$$a = \frac{\Delta v}{\Delta t} = \frac{v_2 - v_1}{t_2 - t_1}$$

si reemplazamos con los valores que tenemos en los instantes 5s y 7s, podemos escribir:

$$a = \frac{10 \frac{m}{s} - 4 \frac{m}{s}}{7s - 5s}$$

y desarrollando, encontramos el valor de la aceleración:

$$a = \frac{6 \frac{m}{s}}{2s} = 3 \frac{m}{s^2}$$

ahora solamente nos falta obtener la velocidad inicial, y si analizamos la ecuación de velocidad, podemos ver que como sabemos la velocidad en ciertos instantes, podemos reemplazar esos valores y despejar la velocidad inicial.

$$v(t) = v_{0} + a \cdot t$$

reemplacemos con la información que tenemos sobre el primer instante $t=5s$:

$$4 \frac{m}{s} = v_{0} + 3 \frac{m}{s^{2}} \cdot 5s$$

despejando $v_{0}$:

$$v_{0} = 4 \frac{m}{s} - 3 \cdot 5 \frac{m \cdot s}{s^{2}}$$

simplificando:

$$v_{0} = 4 \frac{m}{s} - 15 \frac{m}{s} = -11 \frac{m}{s}$$

podemos verificar que nuestro resultado de velocidad inicial es correcto, al reemplazar en la ecuación de velocidad la información que tenemos del otro instante, y el resultado será el mismo, veamos:

$$v(t) = v_{0} + a \cdot t$$

$$10 \frac{m}{s}= v_{0} + 3 \frac{m}{s^{2}} \cdot 7s$$

$$v_{0} =  10 \frac{m}{s} - 3 \cdot 7 \frac{m \cdot s}{s^{2}}  $$

$$v_{0} =  10 \frac{m}{s}  - 21 \frac{m}{s}$$

$$v_{0} =  -11 \frac{m}{s}$$

el mismo resultado!

como ahora sabemos la velocidad inicial y la aceleración, podemos construir la ecuación de velocidad para todo instante t, que queda así:

$$v(t) = -11 \frac{m}{s} + 3 \frac{m}{s^{2}} \cdot t$$

b)

ahora tenemos este sistema de ecuaciones, donde queremos encontrar en qué instante los dos cuerpos tienen la misma velocidad, lo que equivale a encontrar la intersección en esta sistema de dos ecuaciones y dos variables: velocidad y tiempo.

$$v(t) = -11 \frac{m}{s} + 3 \frac{m}{s^{2}} \cdot t \brack v(t) = 5 \frac{m}{s} -3 \frac{m}{s^{2}} \cdot t$$

primero analizamos que la primera ecuación parte con una velocidad negativa y como tiene una aceleración positiva, a medida que transcurre el tiempo la velocidad aumenta. en caso contrario, la segunda ecuación tiene una velocidad inicial positiva, y una aceleración negativa, así que a medida que transcurre el tiempo la velocidad disminuye.

así podemos ver que estas rectas tendrán un punto de intersección, de hecho en general dos rectas tienen estas posibilidades:

| intersección | valor inicial (v0) | pendiente (a) | las rectas...          |
| :----------- | :----------------- | :------------ | :--------------------- |
| infinitas    | igual              | igual         | son idénticas          |
| ninguna      | distinto           | igual         | son paralelas          |
| una          | da lo mismo        | distinta      | se intersectan una vez |

cuando las velocidades son iguales, podemos igualar los lados derechos de las ecuaciones, resultando en:

$$ -11 \frac{m}{s} + 3 \frac{m}{s^{2}} \cdot t = 5 \frac{m}{s} -3 \frac{m}{s^{2}} \cdot t$$

ahora tenemos que despejar el tiempo t, para lo que tenemos que hacer operaciones a ambos lados:

$$ -11 \frac{m}{s} + 6 \frac{m}{s^{2}} \cdot t = 5 \frac{m}{s} $$

$$ 6 \frac{m}{s^{2}} \cdot t = 16 \frac{m}{s} $$

$$ 6 \frac{1}{s} \cdot t = 16 $$

$$t = \frac{16}{6} s = \frac{8}{3} s \approx 2.66 s$$

listo tenemos el instante en que las velocidades son iguales!

ahora podemos reemplazar ese valor de tiempo en cualquiera de las ecuaciones de velocidad, y resultarán en la velocidad.

para encontrar ahora la velocidad, basta con reemplazar ese instante en cualquiera de las ecuaciones y el resultado de la velocidad será el mismo.

$$v(t=\frac{8}{3} s) = -11 \frac{m}{s} + 3 \frac{m}{s^{2}} \cdot \frac{8}{3} s$$

y despejando:

$$v(t=\frac{8}{3} s) = -11 \frac{m}{s} + \frac{m}{s} \cdot 8  = -3 \frac{m}{s}$$

para verificar que el resultado es correcto, reemplacemos el tiempo en la otra ecuación de velocidad:

$$v(t=\frac{8}{3} s) = 5 \frac{m}{s} - 3 \frac{m}{s^{2}} \cdot \frac{8}{3} s = 5 \frac{m}{s} - 8 \frac{m}{s} = -3 \frac{m}{s}$$

con esto, tenemos que la respuesta que las velocidades serán iguales, su valor será -3 metros/ segundos cuadrados, esto ocurrirá en el instante 8/3 segundos$.

## ejercicio-02 (30 min)

veamos ahora en 2 dimensiones, de forma vectorial

## ejercicio-03 (30 min)
