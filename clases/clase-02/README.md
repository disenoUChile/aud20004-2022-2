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

## Leyes de Newton (15 min)

Newton, nacido en 1643, publició en 1687 su libro "Principios matemáticos de filosofía natural", donde expone sus ley de gravitación universal, donde si tenemos dos cuerpos de masa $m_1$ y $m_2$ y posiciones $\vec{x_1}$ y $\vec{x_2}$, podemos escribir la fuerza gravitacional que hace el cuerpo 1 sobre el 2 como:

$$\vec{F_{1, 2}} = G \frac{m_1 \cdot m_2}{{\vec{x_1} - \vec{x_2}} \cdot \vec{x_{1,2}}$$

## videos de repaso

estos videos están disponibles con subtítulos en español

- https://www.khanacademy.org/science/ap-college-physics-1/
  - ver sección "Position, acceleration, and velocity"
