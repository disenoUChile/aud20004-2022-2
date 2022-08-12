# clase-02

martes 16 agosto 2022, presencial

## repaso clase anterior y programa hoy (15 min)

la clase anterior repasamos conceptos básicos de matemática, incluyendo:

- sistemas de ecuaciones
- sistema de coordenadas
- unidades de medida
- sistema métrico e imperial

la clase de hoy es la unidad 0: vectores y fuerzas

- escalares
- vectores
- fuerzas
- 3 leyes de Newton

## escalares (15 min)

un escalar posee:

- una magnitud, medida en cierta unidad

ejemplos de escalares en fīsica:

- masa, medida en gramos
- distancia, medida en metros
- área, medida en metros cuadrados
- volumen, medido en metros cúbicos
- tiempo, medido en segundos
- temperatura, medida en grados Celsius
- carga eléctrica, medida en Coulomb

## aritmética de escalares (15 min)

para hacer aritmética (suma, resta, multiplicación y división) entre vectores, basta con trabajar estas cantidades como si fueran números, y respetar las unidades, teniendo mucho cuidado con las equivalencias entre unidades.

## vectores (15 min)

un vector posee:

- una magnitud, medida en cierta unidad
- una dirección (y un sentido), medida en cierto sistema de referencia

ejemplos de vectores en física:

- posición o desplazamiento, medido en $m$
- velocidad, medida en $\frac{m}{s}$
- aceleración, medida en $\frac{m}{s^2}$

## sistemas de referencia de vectores (15 min)

si queremos representar cualquier punto en el plano XY, debemos hacer los siguientes pasos:

- definir un origen (0, 0)
- definir dirección y sentido del eje x, llamada $\hat{x}$
- definir dirección y sentido del eje y, llamada $\hat{y}$

un vector con gorrito como \hat{x}$ es un vector especial, llamado vector unitario, porque su magnitud es 1.

el sistema cartesiano, en honor a René Descartes, es el que hemos usado hasta hora, donde definimos los vectores unitarios $\hat{x}$ $\hat{y}$ y perpendiculares, con los que podemos describir cualquier posición $\vec{P} = (x, y)$ en el plano, como la siguiente suma:

$$\vec{P} = x \cdot \hat{x} + y \cdot \hat{y}$$

por ejemplo, el punto $\vec{C} = (-11, 3)$ puede ser descrito así:

$$\vec{C} = (-11, 3) = -11 \cdot \hat{x} + 3 \cdot \hat{y}$$

notar que podemos describir cualquier punto en el plano XY como la suma ponderada de los vectores unitarios $\hat{x}$ y $\hat{y}$ porque estos vectores son perpendiculares, y permiten movernos a lo largo de todo el plano. pero estos vectores no tienen que ser perpendiculares, basta con que no sean paralelos.

otra manera de representar el plano es de forma polar, con un vector unitario de radio $\hat{r}$, y un ángulo $\theta$.

para convertir entre coordenadas cartesianas y polares, consideremos el vector $\vec{P}$

$$\vec{P} = (x, y) = x \hat{x} + y \hat{y}$$

si dibujamos la distancia entre el origen y el punto P y le llamamos $r$, podemos notar que r es la hipotenusa, y los valores de $x$ e $y$ los catetos de un triángulo rectángulo. si llamamos $\theta$ al ángulo entre eje X y r, podemos usar las identidades de seno y coseno del triángulo rectángulo.

$$sin(\theta) = \frac{cateto opuesto}{hipotenusa} = \frac{y}{r}$$

$$cos(\theta) = \frac{cateto adyacente}{hipotenusa} = \frac{x}{r}$$

y si despejamos $x$ e $y$ de estas ecucaciones obtenemos las siguientes expresiones para convertir de coordenadas polares a cartesianas:

$$x = r \cdot cos(\theta)$$

$$y = r \cdot sin(\theta)$$

y si queremos hacer lo inverso, convertir de coordenadas a cartesianas, tenemos las ecuaciones:

$$r = \sqrt{x^2 + y^2}$$

$$\theta = atan2(x, y)$$

donde atan2 es una versión especial de la arcotangente

para más info revisar acá: https://es.wikipedia.org/wiki/Coordenadas_polares

## aritmética de vectores (15 min)

### suma y resta de vectores

para sumar y restar vectores, podemos descomponer en distintas coordenadas y tratarlas por separado.

por ejemplo:

$$\vec{A} = 5 \hat{x} + 3 \hat{y} \brack \vec{B} = 7 \hat{x} - 1 \hat{y}$$

si sumamos los vectores $\vec{A}$ y $\vec{B}$, obtenemos:

$$\vec{A} + \vec{B} =  (5 \hat{x} + 3 \hat{y}) + (7 \hat{x} - 1 \hat{y}) = (5 + 7) \hat{x} + (3 - 1) \hat{y} = 12 \hat{x} + 2 \hat{y}$$

y si restamos los vectores $\vec{A}$ y $\vec{B}$, obtenemos:

$$\vec{A} - \vec{B} = (5 \hat{x} + 3 \hat{y}) - (7 \hat{x} - 1 \hat{y}) = (5 - 7) \hat{x} + (3 - (-1)) \hat{y} = -2 \hat{x} + 4 \hat{y}$$

### multiplicación y división de vectores por escalares

multiplicar y dividir vectores por un escalar, permite escalar cada una de las componentes del vector.

por ejemplo si multiplicamos el vector $\vec{A}$ por el escalar 5:

$$5 \cdot \vec{A} = 5 \cdot (5 \hat{x} + 3 \hat{y}) = (5 \cdot 5) \hat{x} + (3 \cdot 5) \hat{y} = 25 \hat{x} + 15 {y}$$

y dividir funciona igual, afectando cada componente, por ejemplo si dividimos el vector B por 2:

$$\frac{1}{2} \cdot \vec{B} = \frac{1}{2} (7 \hat{x} - 1 \hat{y}) = \frac{7}{2} \hat{x} - \frac{1}{2} \hat{y} = 3.5 \hat{x}$ - 0.5 \hat{y}$$

## fuerzas (15 min)

una fuerza en física es una influencia que puede hacer cambiar el movimiento de un cuerpo.

una fuerza es un vector: tiene una magnitud y una dirección.

las fuerzas se miden en Newton (N), que equivale a $\frac{kg \cdot m}{s^2}$.

en la naturaleza conocemos 4 fuerzas fundamentales:

estas 2 tienen un alcance infinito:

- fuerza gravitatoria: atracción entre entre cuerpos con masa.
- fuerza electromagnética: atracción o repulsión entre cuerpos con carga.

estas 2 actúan a corta distancia:

- fuerza nuclear fuerte: mantiene unidos los núcleos atómicos.
- fuerza nuclear débil: escapa de los contenidos de este curso :)

## antes de Newton (15 min)

Aristóteles (~300 a.C.), postulaba que el estado natural de los cuerpos es el reposo. que para sacarlos del reposo, se le aplica una fuerza, y con esto los cuerpos adquieren velocidad. y que esta relación es directamente proporcional a la masa, resultado en la ecuación ahora desechada por la física:

$$\vec{F} = m \cdot \vec{v}$$

un elemento fundamental que no fue incluido en este modelo, fue la consideración de fuerzas como el roce o fricción. la física de Aristóteles también postulaba que cuando los cuerpos caen en caída libre, los objetos más pesados caen más rápido que los objetos más livianos.

esta observación viene de haber considerado solamente la experiencia de estar dentro de un fluido, en nuestro caso, el aire, la atmósfera. un fluido opone resistencia a la caída libre según la forma o área del cuerpo, y eso ocasiona roce, que se opone a la fuerza de gravedad y hace que distintos objetos caigan a velocidades distintas.

pero en el vacío, todos los cuerpos, independiente de su masa, son solamente afectados por la gravedad, y caen con la misma aceleración.

esta concepción del movimiento duró dos mil años, hasta Newton.

## Leyes de movimiento de Newton (15 min)

Newton, nacido en 1643, publicó en 1687 su libro "Principios matemáticos de filosofía natural", donde expone sus 3 leyes de movimiento.

### Primera ley de Newton: inercia

todos los cuerpos permanecen moviéndose en línea recta a velocidad constante, hasta que se le aplica una fuerza externa.

consecuencias:

- si observamos un objeto descansando en una mesa, está moviéndose en línea recta con velocidad constante, lo que pasa es que esta velocidad es cero.
- si hacemos esta afirmación mientras estamos sin movernos, notamos que estamos asumiendo el planeta como sin moverse, cuando en realidad se está moviendo en torno al sol!
- es relativo, no existe un standard absoluto de reposo, siempre hay que definir un origen y un sistema de coordenadas.

### Segunda ley de newton: momentum

momentum $\vec{p}$ se define como la cantidad de movimiento, y es el producto entre masa $m$ y velocidad $\vec{p} de un cuerpo$.

$$\vec{p} = m /cdot \vec{v}$$

el cambio de momentum de un objeto es proporcional a la fuerza aplicada y ocurre en la dirección de la fuerza aplicada. eso en matemáticas, implica que la derivada del momentum es la fuerza, esto es.

$$\vec{F} = \frac{d \vec{p}}{dt} = \frac{d (m \cdot \vec{v})}{dt}$$

si la masa $m$ es constante, podemos simplificar así:

$$\vec{F} =  m \frac{d (\vec{v})}{dt} = m \cdot \vec{a}$$

lo que resulta en que la fuerza es igual al producto entre masa y aceleración.

### Tercera ley de newton: acción y reacción

para cada acción siempre hay una opuesta de igual magnitud.

ojo: las fuerzas no se anulan, porque se aplican en cuerpos distintos. ejemplo:

si una pelota está reposando en la superficie de la tierra, la fuerza de gravedad que ejerce la tierra sobre la pelota, tiene su reacción en la fuerza opuesta: la atracción que ejerce la pelota por sobre la tierra.

si la pelota está en reposo, no es porque esas fuerzas se anulen, es porque la fuerza de atracción que ejerce la tierra sobre la pelota, es contrarrestada por la fuerza normal que ejerce la superficie de la tierra sobre la pelota. estas dos fuerzas actuando sobre la pelota se contrarrestan, haciendo que $\vec{F} = 0$, y por lo tanto, aceleración cero, y con eso, velocidad constante.

## ley de gravitación universal de Newton

como ya vimos, existen 4 fuerzas fundamentales de la naturaleza, y en este curso estudiaremos 2: las gravitatoria y la electromagnética.

otro avance que hizo Newton, fue a través de experiencias empíricas, fue definir la ley de gravitación universal, con una ecuación que describe el vector $\vec{F}$ de fuerza entre dos cuerpos, donde:

- sus masas son $m_1$ y $m_2$
- sus posiciones son $\vec{x_1}$ y $\vec{x_2}$
- la distancia entre los cuerpos es $r$, que en 2D es: $r = \sqrt{(x_1-x_2)^2 + (y_1-y_2)^2}$

esta ley de gravitación universal postula que existe una fuerza gravitacional que hace cada cuerpo contra el otro que cumple con:

- ser directamente proporcional a cada masa $m_1$ y $m_2$
- ser inversamente proporcional a $r^2$, la distancia entre los cuerpos al cuadrado
- ser una fuerza atractiva, con $m_1$ atrayendo a $m_2$, y a su vez, $m_2$ atrayendo a $m_1$
- tener una constante de proporcionalidad universal llamada $G$

la ecuación entonces resulta:

$$F = G \frac{m_1 \cdot m_2}{r^2}$$

esa ecuación es útil para encontrar la magnitud de estas fuerzas ejercidas entre los cuerpos, y si queremos encontrar los vectores fuerza, basta con multiplicar ese escalar $F$ por una dirección.

si notamos $\vec{F_{1,2}}$ como la fuerza que hace la $m_1$ sobre $m_2$, y $\hat{r_{2,1}}$ como el vector unitario que va desde $m_2$ a $m_1$ podemos escribir así la ecuación:

$$\vec{F_{1,2}} = F \cdot \hat{r_{2,1}} = G \frac{m_1 \cdot m_2}{r^2} \cdot \hat{r_{2, 1}}$$

## videos de repaso

estos videos están disponibles con subtítulos en español

- https://www.khanacademy.org/science/ap-college-physics-1/
  - ver sección "Position, acceleration, and velocity"
