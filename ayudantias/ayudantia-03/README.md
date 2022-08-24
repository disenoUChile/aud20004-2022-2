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

con esto, tenemos que la respuesta que las velocidades serán iguales, su valor será -3 metros / segundos cuadrados, esto ocurrirá en el instante 8/3 segundos.

## ejercicio-02 (30 min)

a)

a partir de la ecuación de posición en 2D:

$$\vec{x}(t) = \vec{x_0} + \vec{v_0} \cdot t + \frac{1}{2} \vec{a} t^2$$

y de los siguientes datos:

- posición inicial es (5, 0) metros
- velocidad inicial es (-1, 2) metros / segundo
- aceleración es (3, -1) metros / segundos cuadrados

cuál es la posición del cuerpo en los instantes 0s, 1s, 2s y 30s?

b) cuál es la ecuación de velocidad en 2D de este cuerpo?
qué velocidad tiene en los instantes 0s, 1s, 2s, 3s?

## solución ejercicio-02

partamos de la ecuación de posición en 2D, y descompongamos en las coordenadas x e y:

$$x(t) = x_0 + v_{x0} \cdot t + \frac{1}{2} a_x \cdot t^2$$

$$y(t) = y_0 + v_{y0} \cdot t + \frac{1}{2} a_y \cdot t^2$$

y reemplacemos los valores en estas ecuaciones:

$$x(t) = 5m + (-1 \frac{m}{s}) \cdot t + \frac{1}{2} \cdot (3 \frac{m}{s^2}) \cdot t^2$$

$$y(t) = 0m + (2 \frac{m}{s}) \cdot t + \frac{1}{2} \cdot (-1 \frac{m}{s^2}) \cdot t^2$$

y simplificando:

$$x(t) = 5m -t \frac{m}{s} + \frac{3 \cdot t^2}{2} \frac{m}{s^2}$$

$$y(t) = 2t \frac{m}{s} - \frac{t^2}{2} \frac{m}{s^2}$$

reemplacemos para los tiempos pedidos en el enunciado, empezamos por 0s:

$$x(t=0s) = 5m -0s \frac{m}{s} + \frac{3 \cdot (0s)^2}{2} \frac{m}{s^2}$$

$$y(t=0s) = 2(0s) \frac{m}{s} - \frac{(0s)^2}{2} \frac{m}{s^2}$$

y despejando:

$$x(t=0s) = 5m$$

$$y(t=0s) = 0m$$

ahora para 1s:

$$x(t=1s) = 5m -(1s) \frac{m}{s} + \frac{3 \cdot (1s)^2}{2} \frac{m}{s^2}$$

$$y(t=1s) = 2(1s) \frac{m}{s} - \frac{(1s)^2}{2} \frac{m}{s^2}$$

y despejando:

$$x(t=1s) = 5m - 1m + \frac{3}{2} m = 4m + 1.5m = 5.5 m$$

$$y(t=1s) = 2m - \frac{1}{2} m = 2m = 0.5m  = 1.5m$$

ahora para 2s:

$$x(t=2s) = 5m -(2s) \frac{m}{s} + \frac{3 \cdot (2s)^2}{2} \frac{m}{s^2}$$

$$y(t=2s) = 2(2s) \frac{m}{s} - \frac{(2s)^2}{2} \frac{m}{s^2}$$

y despejando:

$$x(t=2s) = 5m - 2m + \frac{3 \cdot 4}{2}m = 3m + 6m = 9m$$

$$y(t=2s) = 4m - \frac{4}{2}m = 2m$$

ahora para 30s:

$$x(t=30s) = 5m -(30s) \frac{m}{s} + \frac{3 \cdot (30s)^2}{2} \frac{m}{s^2}$$

$$y(t=30s) = 2(30s) \frac{m}{s} - \frac{(30s)^2}{2} \frac{m}{s^2}$$

y despejando:

$$x(t=30s) = 5m - 30m + \frac{3 \cdot 900}{2}m = -25m + 1350m = 1325m$$

$$y(t=30s) = 60m - \frac{900}{2}m = 60m - 450m = -390m$$

gráficos en Wolfram Alpha de x(t):

- ecuación x(t): https://www.wolframalpha.com/input?i=x%28t%29+%3D+5+-t+%2B+%283*t%5E2%2F2%29+
- x(t=0s): https://www.wolframalpha.com/input?i=x%28t%29+%3D+5+-t+%2B+%283*t%5E2%2F2%29+where+t%3D0
- x(t=1s): https://www.wolframalpha.com/input?i=x%28t%29+%3D+5+-t+%2B+%283*t%5E2%2F2%29+where+t%3D1
- x(t=2s): https://www.wolframalpha.com/input?i=x%28t%29+%3D+5+-t+%2B+%283*t%5E2%2F2%29+where+t%3D2
- x(t=30s): https://www.wolframalpha.com/input?i=x%28t%29+%3D+5+-t+%2B+%283*t%5E2%2F2%29+where+t%3D30

gráficos en Wolfram Alpha de y(t):

- ecuación y(t): https://www.wolframalpha.com/input?i=y%28t%29+%3D+2*t+-+%28t%5E2%2F2%29+
- y(t=0s): https://www.wolframalpha.com/input?i=y%28t%29+%3D+2*t+-+%28t%5E2%2F2%29+where+t%3D0
- y(t=1s): https://www.wolframalpha.com/input?i=y%28t%29+%3D+2*t+-+%28t%5E2%2F2%29+where+t%3D1
- y(t=2s): https://www.wolframalpha.com/input?i=y%28t%29+%3D+2*t+-+%28t%5E2%2F2%29+where+t%3D2
- y(t=30s):

b)

en general la ecuación de velocidad en 2D es:

$$\vec{v}(t) = \vec{v_0} + \vec{a} \cdot t$$

y si descomponemos en el eje x y en el eje y tenemos:

$$v_{x}(t) = v_{x0} + a_{x} \cdot t$$

$$v_{y}(t) = v_{y0} + a_{y} \cdot t$$

y conocemos los parámetros que necesitamos, que son las velocidades inicial y las aceleraciones, así que reemplazamos esos valores y tenemos las ecuaciones pedidas.

$$v_{x}(t) = -1 \frac{m}{s} + (3\frac{m}{s^2}) \cdot t$$

$$v_{y}(t) = 2 \frac{m}{s} + (-1\frac{m}{s^2}) \cdot t$$

notamos que las ecuaciones de la velocidad del cuerpo en eje X y eye Y son rectas, donde la aceleración es la pendiente de esa recta.

ahora reemplazamos en cada instante y obtenemos los valores, empezando por 0s:

$$v_{x}(t=0s) = -1 \frac{m}{s} + (3\frac{m}{s^2}) \cdot (0s)$$

$$v_{y}(t=0s) = 2 \frac{m}{s} + (-1\frac{m}{s^2}) \cdot (0s)$$

y despejando:

$$v_{x}(t=0s) = -1 \frac{m}{s}$$

$$v_{y}(t=0s) = 2 \frac{m}{s}$$

ahora para 1s:

$$v_{x}(t=1s) = (-1 \frac{m}{s}) + (3\frac{m}{s^2}) \cdot (1s)$$

$$v_{y}(t=1s) = (2 \frac{m}{s}) + (-1\frac{m}{s^2}) \cdot (1s)$$

y despejando:

$$v_{x}(t=1s) = -1 \frac{m}{s} + 3\frac{m}{s} = 2 \frac{m}{s}$$

$$v_{y}(t=1s) = 2 \frac{m}{s} - 1\frac{m}{s} = 1 \frac{m}{s}$$

ahora para 2s:

$$v_{x}(t=2s) = -1 \frac{m}{s} + (3\frac{m}{s^2}) \cdot (2s)$$

$$v_{y}(t=2s) = 2 \frac{m}{s} + (-1\frac{m}{s^2}) \cdot (2s)$$

y despejando:

$$v_{x}(t=2s) = -1 \frac{m}{s} + 6\frac{m}{s} = 5 \frac{m}{s}$$

$$v_{y}(t=2s) = 2 \frac{m}{s} -2\frac{m}{s} = 0 \frac{m}{s}$$

ahora para 3s:

$$v_{x}(t=3s) = -1 \frac{m}{s} + (3\frac{m}{s^2}) \cdot (3s)$$

$$v_{y}(t=3s) = 2 \frac{m}{s} + (-1\frac{m}{s^2}) \cdot (3s)$$

y despejando:

$$v_{x}(t=3s) = -1 \frac{m}{s} + 9\frac{m}{s} = 8 \frac{m}{s}$$

$$v_{y}(t=3s) = 2 \frac{m}{s} - 3 \frac{m}{s} = -1 \frac{m}{s}$$

gráficos en Wolfram Alpha de v(t) para eje x:

- ecuación v(t): https://www.wolframalpha.com/input?i=v%28t%29+%3D+-1+%2B+3*t
- v(t=0s): https://www.wolframalpha.com/input?i=v%28t%29+%3D+-1+%2B+3*t+where+t%3D0
- v(t=1s): https://www.wolframalpha.com/input?i=v%28t%29+%3D+-1+%2B+3*t+where+t%3D1
- v(t=2s): https://www.wolframalpha.com/input?i=v%28t%29+%3D+-1+%2B+3*t+where+t%3D2
- v(t=3s): https://www.wolframalpha.com/input?i=v%28t%29+%3D+-1+%2B+3*t+where+t%3D3

gráficos en Wolfram Alpha de v(t) para eje y:

- ecuación v(t): https://www.wolframalpha.com/input?i=v%28t%29+%3D+2+-+t
- v(t=0s): https://www.wolframalpha.com/input?i=v%28t%29+%3D+2+-+t+where+t%3D0
- v(t=1s): https://www.wolframalpha.com/input?i=v%28t%29+%3D+2+-+t+where+t%3D1
- v(t=2s): https://www.wolframalpha.com/input?i=v%28t%29+%3D+2+-+t+where+t%3D2
- v(t=3s): https://www.wolframalpha.com/input?i=v%28t%29+%3D+2+-+t+where+t%3D3

gráficos en Wolfram Alpha de vy(t):

## ejercicio-03 (30 min)

a) si tenemos esta ecuación de posición de un cuerpo en 1D:

$$x(t) = x_0 + v_0 \cdot t + \frac{1}{2} a \cdot t^2$$

y sabemos que:

- posición inicial es (1/4) metro.
- velocidad inicial es 5 metros / segundo.
- aceleración es 9 metros / segundos cuadrados.

a) determinar la ecuación de posición, y a partir de ella, ver en qué instantes de tiempo la posición es 0m.

b) determinar la posición máxima o mínima de la posición, si sabemos la pista que la posición máxima ocurre cuando la velocidad es cero.

## solución ejercicio-03

a)

reemplazando con los valores del enunciado, la ecuación de posición es:

$$x(t) = \frac{1}{4}m + 5t \frac{m}{s} + \frac{9 \cdot t^2}{2}$$

podemos ordenar esta ecuación también de esta manera:

$$x(t) = 4.5 \frac{m}{s^2} \cdot t^2 + 5t \frac{m}{s} + \frac{1}{4}m$$

si queremos saber el instante de tiempo donde la posición es 0m, la ecuación resulta:

$$0m = 4.5 \frac{m}{s^2} \cdot t^2 + 5t \frac{m}{s} + \frac{1}{4}m$$

y si comparamos con la ecuación cuadrática canónica:

$$0 = A t^2 + Bt + C$$,

vemos que nuestro A=4.5, B=5, C=1/4.

también que los valores de t que hacen que esta ecuación sea igual a 0, son:

$$t = \frac{-B \pm \sqrt{B^2 - 4 \cdot A \cdot C}}{2 \cdot A}$$

y reemplazando, obtenemos:
