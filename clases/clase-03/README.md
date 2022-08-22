# clase-03

martes 23 agosto 2022, presencial

## repaso clase anterior y programa hoy (15 min)

la clase anterior repasamos conceptos básicos de matemática, incluyendo:

- escalares
- vectores
- fuerzas
- 3 leyes de Newton
- ley de gravitación universal

la clase de hoy es la unidad 0: cinemática en 1 y 2 dimensiones

- definición de cinemática
- ecuación de velocidad en 1D
- ecuación de velocidad en 2D
- ecuación de posición en 1D
- ecuación de posición en 2D

## definición de cinemática

en cinemática, describiremos y modelaremos los vectores de posición $\vec{x}$, velocidad $\vec{v}$ y de aceleración $\vec{a}$ de cuerpos, sin importar las fuerzas ni las causas de estos movimientos.

## notación en cinemática

en 1D:

- posición: $x(t)$
- velocidad: $v(t)$
- aceleración: $a(t)$

en 2D:

- posición: $\vec{x}(t)$, descomponemos en $x(t)$, $y(t)$.
- velocidad: $\vec{v}(t)$, descomponemos en $v_{x}(t)$, $v_{y}(t)$.
- aceleración: $\vec{a}(t)$, descomponemos en $a_{x}(t)$, $a_{y}(t)$.

adicionales:

- $\Delta$: significa diferencia entre dos cantidades.
- $algo_{0}$: el subíndice 0 implica en instante t=0, que llamamos inicial.

## supuestos y simplificaciones de cinemática

- un cuerpo se puede describir con una posición en un punto
- en ese punto, está toda la masa del cuerpo

## relaciones entre posición, velocidad y aceleración:

- aceleración es cambio de velocidad en el tiempo.

$$a(\Delta t) = \frac{\Delta v}{\Delta t}$$

donde $\Delta$ significa diferencia, y la ecuación anterior se lee como la aceleración en una ventana de tiempo, es igual a la variación de velocidad en esa ventana de tiempo, dividida por la ventana de tiempo.

- velocidad es cambio de posición el tiempo.

$$v(\Delta t) = \frac{\Delta x}{\Delta t}$$

## ecuación de velocidad en una dimensión (1D)

si conocemos la aceleración promedio $\overline{a}$ en un instante, podemos usar como ventana de tiempo el tiempo entre origen $t_0 = 0$ y ese instante, y así escribir la aceleración en ese instante de tiempo entre ellos como:

$$\overline{a} =  \frac{v(t) - v(t_0)}{t - t_0}$$

podemos simplificar ya que sabemos que $t_0 = 0 s$, entonces:

$$\overline{a} = \frac{v(t) - v(t_0)}{t}$$

y sabemos que $v(t_0)$ es la velocidad inicial en instante $t=0$, y es una constante, que podemos llamar $v_0$, entonces:

$$\overline{a} = \frac{v(t) - v_0}{t}$$

y despejando la velocidad $v(t)$, tenemos la ecuación de velocidad:

$$v(t) =  v_0 + \overline{a} \cdot t$$

## ecuación de posición en una dimensión (1D)

la posición $x(t)$ en el instante de tiempo t, es igual a la posición inicial $x_0$ más el producto entre la velocidad promedio $\overline{v}$ y el tiempo t.

$$x(t) = x_0 + v_{promedio} \cdot t$$

a su vez, la velocidad promedio $v$ la podemos plantear como:

$$v_{promedio} =  \frac{v(t) + v_0}{2}$$

y a su vez, podemos escribir $v(t)$ en función de $v_0$ y $a$:

$$v_{promedio} =  \frac{(v_0 + a \cdot t) + v_0}{2} = v_0 + \frac{a \cdot t}{2}$$

y reemplazando en la ecuación de posición x(t) resulta en:

$$x(t) = x_0 + (v_0 + \frac{a \cdot t}{2}) \cdot t$$

y desarrollando:

$$x(t) = x_0 + v_0 \cdot t + \frac{1}{2} a \cdot t$$

HASTA AQUI

$$v =  \frac{x(t) - x(t_0)}{t - t_0}$$

y haciendo las mismas simplificaciones anteriores de $t_0 = 0$ y $x(t_0) = x_0$, podemos escribir:

$v =  \frac{x(t) - x_0}{t}$

y despejando $x(t)$:

$$x(t) = x_0 + v \cdot t$$

y reemplazando con la ecuación de velocidad anterior:

$$x(t) = x_0 + (v_0 + a \cdot t) \cdot t$$

y agrupando:

$$x(t) = x_0 + v_0 \cdot t + a \cdot t^2$$

## ecuación de velocidad en 1D

ecuación de velocidad, en función de aceleración:

$$\vec{v}(t) = \vec{v_{0}} + \vec{a} \cdot t$$

si tenemos una dimensión (1D), podemos simplificar esto y decir:

$$v(t) = v_{0} + a \cdot t$$

en dos dimensiones (2D) tenemos el sistema:

$$v_{x}(t) = v_{x0} + a_{x} \cdot t \brack v_{y}(t) = v_{y0} + a_{y} \cdot t$$

## ecuación de posición en 1D y 2D

$$\vec{x}(t) = \vec{x_{0}} + \vec{v_{0}} \cdot t + \frac{1}{2} \cdot \vec{a} \cdot t^2$$

en dos dimensiones (2D) tenemos el sistema:

$$x(t) = x_{0} + v_{x0} \cdot t + \frac{1}{2} \cdot a_{x} \cdot t^2 \brack y(t) = y_{0} + v_{y0} \cdot t + \frac{1}{2} \cdot a{y} \cdot t^2$$

$$
$$
