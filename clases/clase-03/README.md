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

$$a(\Delta t) = \frac{\Delta v}{\Delta t} = \frac{v_2 - v_1}{t_2 - t_1}$$

donde $\Delta$ significa diferencia, y la ecuación anterior se lee como la aceleración en una ventana de tiempo, es igual a la variación de velocidad en esa ventana de tiempo, dividida por la ventana de tiempo.

- velocidad es cambio de posición el tiempo.

$$v(\Delta t) = \frac{\Delta x}{\Delta t} = \frac{x_2 - x_1}{t_2 - t_1}$$

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

$$x(t) = x_0 + \overline{v} \cdot t$$

a su vez, la velocidad promedio $\overline{v}$ la podemos plantear como:

$$\overline{v} =  \frac{v(t) + v_0}{2}$$

y a su vez, podemos escribir $v(t)$ en función de $v_0$ y $a$:

$$\overline{v} =  \frac{(v_0 + \overline{a} \cdot t) + v_0}{2} = v_0 + \frac{\overline{a} \cdot t}{2}$$

y reemplazando en la ecuación de posición x(t) resulta en:

$$x(t) = x_0 + (v_0 + \frac{\overline{a} \cdot t}{2}) \cdot t$$

y desarrollando:

$$x(t) = x_0 + v_0 \cdot t + \frac{1}{2} \overline{a} \cdot t^2$$

## resumen cinemática en 1D

con aceleración promedio $\overline{a}$, podemos escribir las ecuaciones de posición y aceleración asi:

$$x(t) = x_0 + v_0 \cdot t + \frac{1}{2} \overline{a} \cdot t^2$$

$$v(t) = v_0 + \overline{a} \cdot t$$

## ecuación de velocidad en 2D

en 2D basta con tomar la ecuación de 1D y reemplazar por vectores:

$$\vec{v}(t) = \vec{v_0} + \vec{\overline{a}} \cdot t$$

y descomponiendo en componentes $\hat{x}$ e $\hat{y}$, tenemos el sistema:

$$v_{x}(t) = v_{x0} + \overline{a}_{x} \cdot t$$

$$v_{y}(t) = v_{y0} + \overline{a}_{y} \cdot t$$

## ecuación de posición en 1D

en 2D basta con tomar la ecuación de 1D y reemplazar por vectores:

$$\vec{x}(t) = \vec{x_0} + \vec{v_0} \cdot t + \frac{1}{2} \vec{\overline{a}} \cdot t^2$$

y descomponiendo en componentes $\hat{x}$ e $\hat{y}$, tenemos el sistema:

$$x(t) = x_0 + v_{x0} \cdot t + \frac{1}{2} \overline{a}_{x} \cdot t^2$$

$$y(t) = y_0 + v_{y0} \cdot t + \frac{1}{2} \overline{a}_{y} \cdot t^2$$

## resumen cinemática en 2D

con aceleración promedio $\vec{\overline{a}}$, podemos escribir las ecuaciones de posición y aceleración asi:

$$x(t) = x_0 + v_{x0} \cdot t + \frac{1}{2} \overline{a}_{x} \cdot t^2$$

$$y(t) = y_0 + v_{y0} \cdot t + \frac{1}{2} \overline{a}_{y} \cdot t^2$$

$$v_{x}(t) = v_{x0} + \overline{a}_{x} \cdot t$$

$$v_{y}(t) = v_{y0} + \overline{a}_{y} \cdot t$$

## comentarios matemáticos sobre estas ecuaciones físicas:

las ecuaciones de velocidad en 1D y 2D del estilo:

$$v(t) = v_{0} + \overline{a} \cdot t$$

las podemos pensar como ecuaciones con variable independiente $t$, donde v es la variable dependiente de t, y donde:

- $\overline{a}$ es la pendiente de la ecuación, por lo tanto su signo nos dice si la velocidad aumenta, disminuye o es constante con el paso del tiempo
- $v_0$: intercepto de la recta $v(t)$ con el eje vertical, donde $t=0$, nos dice la velocidad inicial.

a su vez, si analizamos las ecuaciones de posición en 1D y 2D del estilo:

$$x(t) = x_0 + v_0 \cdot t + \frac{1}{2} \overline{a} \cdot t^2$$

podemos ver que

## ecuaciones de cinemática sin tiempo en 1D

otra manera de ver la posición en un determinado momento es:

$$x(t) = x_0 + \overline{v} \cdot t$$

donde tenemos:

- $x(t)$: posición en instante t
- $x_0$: posición inicial
- $\overline{v}$: velocidad promedio
- t: instante t

si queremos eliminar la dependencia en $t$, podemos despejarlo desde la ecuación original de velocidad $v(t)$:

$$v(t) = v_0 + \overline{a} \cdot t$$

y despejando $t$:

$$t = \frac{v(t) - v{0}}{\overline{a}}$$

y reemplazando este t en la ecuación de posición:

$$x(t) = x_0 + \overline{v} \cdot t = x_0 + \overline{v} \cdot \frac{v(t) - v{0}}{\overline{a}}$$
