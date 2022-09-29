# clase-07

martes 27 septiembre 2022, presencial

repaso y ejercicios unidades 0, 1, 2, 3 y 4

## unidad 0: vectores y fuerzas

una fuerza en física es una influencia que puede hacer cambiar el movimiento de un cuerpo.

una fuerza es un vector: tiene una magnitud y una dirección y se miden en Newton (N).

$$1N = 1\frac{kg \cdot m}{s^2}$$

primera ley de Newton (inercia): todos los cuerpos permanecen moviéndose en línea recta a velocidad constante, hasta que se le aplica una fuerza externa.

segunda ley de newton (momentum):

el cambio de momentum de un objeto es proporcional a la fuerza aplicada y ocurre en la dirección de la fuerza aplicada. eso en matemáticas, implica que la derivada del momentum es la fuerza, esto es.

$$\vec{F} = \frac{d \vec{p}}{dt} = \frac{d (m \cdot \vec{v})}{dt}$$

si la masa m es constante, podemos simplificar así:

$$\vec{F} =  m \frac{d (\vec{v})}{dt} = m \cdot \vec{a}$$

lo que resulta en que la fuerza es igual al producto entre masa y aceleración.

tercera ley de newton (acción y reacción): para cada acción siempre hay una opuesta de igual magnitud. ojo: las fuerzas no se anulan, porque se aplican en cuerpos distintos.

ley de gravitación universal de Newton:

- tenemos masas m1 y m2
- sus posiciones son los vectores x1 y x2.
- la distancia entre los cuerpos es r, que en 2D es:

$$r = \sqrt{(x_1-x_2)^2 + (y_1-y_2)^2}$$

esta ley de gravitación universal postula que existe una fuerza gravitacional que hace cada cuerpo contra el otro que cumple con:

- ser directamente proporcional a cada masa m1 y m2
- ser inversamente proporcional a radio al cuadrado, la distancia entre los cuerpos al cuadrado
- ser una fuerza atractiva, con m1 atrayendo a m2, y a su vez, m2 atrayendo a m1
- tener una constante de proporcionalidad universal llamada G

la ecuación entonces resulta:

$$F = G \frac{m_1 \cdot m_2}{r^2}$$

## unidad 1: cinemática en 1D y 2D

en cinemática, describiremos y modelaremos los vectores de posición x, velocidad v y de aceleración a de cuerpos, sin importar las fuerzas ni las causas de estos movimientos.

- posición: x(t), medida en m
- velocidad: v(t), medida en m/s
- aceleración: a(t), medida en m/s^2

usamos la letra griega Delta mayúscula para denotar diferencia entre valor final y valor inicial

$$\Delta = Delta = final - inicial$$

supuestos y simplificaciones que haremos en cinemática:

- un cuerpo se puede describir con una posición en un punto
- en ese punto, está toda la masa del cuerpo
- la gravedad en la tierra es constante e igual a 10 metros / segundos cuadrados
- no hay atmósfera, y por lo tanto, no hay roce

aceleración es cambio de velocidad en el tiempo, y velocidad es cambio de posición en el tiempo.

$$a(\Delta t) = \frac{\Delta v}{\Delta t} = \frac{v_2 - v_1}{t_2 - t_1}$$

$$v(\Delta t) = \frac{\Delta x}{\Delta t} = \frac{x_2 - x_1}{t_2 - t_1}$$

en este curso simplificaremos nuestros cálculos, usando una aceleración promedio, que notaremos como a y es una constante, entonces:

$$a(t) = a$$

nuestra aceleración será un número constante, y no dependerá del tiempo, o en otras palabras, tendrá el mismo valor para todo instante de tiempo.

si conocemos la aceleración promedio a en un instante, podemos usar como ventana de tiempo el tiempo entre origen t=0s y ese instante, y así escribir la aceleración en ese instante de tiempo entre ellos como:

$$a =  \frac{v(t) - v(t_0)}{t - t_0}$$

podemos simplificar, ya que sabemos que el instante inicial es 0s y si llamamos velocidad sub cero a la velocidad inicial:

$$v(t) =  v_0 + a \cdot t$$

la posición x(t) en el instante de tiempo t, es igual a la posición inicial $x_0$ más el producto entre la velocidad promedio v y el tiempo t.

$$x(t) = x_0 + v_{promedio} \cdot t$$

a su vez, la velocidad promedio la podemos plantear como:

$$v_{promedio} =  \frac{v(t) + v_0}{2}$$

y con esot

$$x(t) = x_0 + v_0 \cdot t + \frac{1}{2} a \cdot t^2$$

con aceleración promedio a, podemos escribir las ecuaciones de posición y aceleración asi:

$$x(t) = x_0 + v_0 \cdot t + \frac{1}{2} \overline{a} \cdot t^2$$

$$v(t) = v_0 + a \cdot t$$

en 2D basta con tomar la ecuación de 1D y reemplazar por vectores:

$$\vec{v}(t) = \vec{v_0} + \vec{a} \cdot t$$

y descomponiendo en componentes x e y, tenemos el sistema:

$$v_{x}(t) = v_{x0} + a_{x} \cdot t$$

$$v_{y}(t) = v_{y0} + a_{y} \cdot t$$

en 2D basta con tomar la ecuación de 1D y reemplazar por vectores:

$$\vec{x}(t) = \vec{x_0} + \vec{v_0} \cdot t + \frac{1}{2} \vec{a} \cdot t^2$$

y descomponiendo en los ejes x e y:

$$x(t) = x_0 + v_{x0} \cdot t + \frac{1}{2} a_{x} \cdot t^2$$

$$y(t) = y_0 + v_{y0} \cdot t + \frac{1}{2} a_{y} \cdot t^2$$

las ecuaciones de velocidad en 1D y 2D del estilo:

$$v(t) = v_{0} + a \cdot t$$

las podemos pensar como ecuaciones con variable independiente t, donde v es la variable dependiente de t, y donde:

- la aceleración es la pendiente de la ecuación, por lo tanto su signo nos dice si la velocidad aumenta, disminuye o es constante con el paso del tiempo.
- la velocidad inicial: intercepto de la recta v(t) con el eje vertical, donde t=0, nos dice la velocidad inicial.

consideraciones de movimientos circulares:

- consideramos una superficie en forma de disco
- se mueve con velocidad angular constante
- nos centramos en un radio del disco, todo ese radio avanza y pasa por el origen con regularidad (periodo T).
- pero un cuerpo a $\frac{R}{2}$ del centro, se más lento que un cuerpo en $R$.

la ecuación es:

$$v = \omega \cdot r$$

donde

- $v$ es velocidad, se mide en $\frac{m}{s}$
- $\omega$ es velocidad angular, se mide en $\frac{radianes}{s}$
- $r$ es radio, se mide en $m$

si tenemos una velocidad angular constante, podemos plantear esta ecuación como:

$$\omega = \frac{v}{r}$$

donde v es directamente proporcional a r, entonces con velocidad angular constante, a mayor radio, mayor velocidad. por lo tanto, un cuerpo muy cerca del centro va más lento que uno a mayor distancia.

## unidad 02: dinámica

en dinámica tomaremos en cuenta las fuerzas y la segunda ecuación de Newton:

$$\vec{F} = m \cdot \vec{a}$$

cuando resolvamos problemos de dinámica, crearemos diagramas de cuerpo libre (DCLs), donde aislaremos cada cuerpo, y dibujaremos todas las fuerzas que le afectan, sin importar su origen.

esto nos permitirá escribir la segunda ecuación de Newton para cada cuerpo, donde la suma de todas las fuerzas sobre un cuerpo es igual a su masa multiplicada por su aceleración.

la fuerza de peso se anota como W, por inglés "weight", se mide en Newton. la ecuación para un cuerpo de masa m sujeta a una gravedad g es:

$$W = m \cdot g$$

la masa es inherente al cuerpo y constante, el peso depende de la gravedad, que es distinta en otros planetas.

la dirección de la fuerza de peso es hacia el centro del planeta, y por la curvatura del planeta tierra, podemos asumir que siempre es perpendicular al suelo y hacia abajo.

la fuerza normal se anota como N, por normal, se mide en Newton. la fuerza normal es una fuerza perpendicular a la superficie de contacto. normal hace referencia al sentido geométrico de perpendicular, no de ordinario.

si somos un cuerpo y estamos en un plano, la fuerza normal y la fuerza de gravedad sobre nosotros se contrarrestan y la sumatoria de fuerzas en nosotros es cero, por lo tanto, no tenemos aceleración.

pero si estamos en un plano inclinado, la fuerza de gravedad sigue apuntando hacia el centro de la tierra, hacia abajo, y la fuerza normal es perpendicular al plano inclinado, en un ángulo, y la ecuación queda:

$$N = m \cdot g \cdot cos(\theta)$$

si esas fueran las dos únicas fuerzas sobre un cuerpo en un plano inclinado, la sumatoria sería siempre distinta de cero para cualquier ángulo distinto de cero, y por lo tanto siempre tendría aceleración.

pero por nuestra experiencia vital sabemos que podemos estar parados, sin acelerar, sobre planos inclinados! eso es porque hay otra fuerza en juego, que es la fuerza de roce.

la fuerza de roce es una fuerza, se mide en Netwon.

la fuerza de roce tiene dos sabores: estático y dinámico.

la fuerza de roce estático es la que se opone a que el cuerpo se deslice, y que les permite a los cuerpos poder estar sobre un plano inclinado sin acelerar.

esta fuerza de roce tiene un máximo valor, que va a ser dependiente del material y del ángulo de inclinación, que después de ser superados, el cuerpo se desliza y ya no tiene fuerza de roce estático.

cuando el cuerpo ya se está moviendo, deja de ser estático, ahora tiene una force de roce dinámico, que depende del material.

en general, el coeficiente de roce estático es mayor que dinámico, por lo que se necesita aplicar una fuerza para vencer el roce estático, y tras ser vencido, se necesita menos fuerza para mantenerlo en movimiento.

fuerza de tensión es una fuerza transmitida por una cuerda ideal, cuya masa es nula y que es inextensible, o sea, su largo es constante. se anota como T, por tensión, y es una fuerza, se mide en Newton.

el caso más simple para entender tensión, es de un cuerpo de masa m, sin acelerar, colgando de una cuerda anclada al techo.

el diagrama de cuerpo libre sobre este cuerpo presenta dos fuerzas:

- la fuerza de peso, ejercida por la tierra atrayendo el cuerpo hacia el suelo.
- la fuerza de tensión, ejercida por el techo y transmitiendo a través de la cuerda, atrayendo el cuerpo hacia el techo.

en el eje Y podemos escribir la ecuación:

$$T - m \cdot g = m \cdot a$$

y si no acelera, entonces:

$$T = m \cdot g$$

este es un caso similar al de un cuerpo sin acelerar en el suelo, donde el peso es contrarrestado por la fuerza normal, pero en este caso no hay fuerza normal, sino que hay fuerza de tensión.

en una máquina de Atwood, tenemos dos cuerpos, con masas m1 y m2 conectados por una cuerda ideal a la misma polea.

nos damos cuenta que si uno acelera, el otro acelera con la misma magnitud y en dirección contraria, porque la cuerda es ideal e inextensible.

entonces si decimos que el cuerpo m1 acelera hacia abajo, escribimos su ecuación según su diagrama de cuerpo libre:

$$T - m_1 \cdot g = m_1 \cdot (-a)$$

y el otro cuerpo, entonces acelera hacia arriba y su ecuación es:

$$T - m_2 \cdot g = m_2 \cdot a$$

si despejamos la tensión de la primera ecuación, resulta:

$$T = m_1 \cdot (g - a)$$

y si reemplazamos esa tensión en la segunda ecuación, resulta:

$$(m_1 \cdot (g - a)) - m_2 \cdot g = m_2 \cdot a$$

expandiendo los términos:

$$m_1 \cdot g - m_1 \cdot a - m_2 \cdot g = m_2 \cdot a$$

agrupando a:

$$m_1 \cdot g - m_2 \cdot g = m_1 \cdot a + m_2 \cdot a$$

y despejando a:

$$a = g \cdot \frac{m1 - m2}{m1+ m2}$$

la aceleración es un múltiplo de la gravedad, y depende de la relación entre las masas, vemos que la aceleración que definimos será positiva cuando m1 sea mayor que m2, y que invertirá su signo cuando m2 sea mayor que m1.

como tenemos a, podemos ahora despejar T:

$$T = m_1 \cdot (g - a) = m_1 \cdot (g - g \cdot \frac{m1 - m2}{m1+ m2})$$

y desarrollando:

$$T = m_1 \cdot g \cdot (1 - \frac{m_1 - m_2}{m_1 + m_2})$$

expresamos 1 como la suma de m1 y m2 dividida por sí misma:

$$T = m_1 \cdot g \cdot (\frac{m_1 + m_2}{m_1 + m_2} - \frac{m_1 - m_2}{m_1 + m_2})$$

y con eso simplificamos:

$$T = m_1 \cdot g \cdot (\frac{2 \cdot m_2}{m_1 + m_2})$$

y resulta una tensión que depende de las masas m1 y m2.

$$T = g \cdot \frac{m_1 \cdot m_2}{m_1 + m_2}$$

notamos que si m_1 y m_2 son iguales, entonces la aceleración se hace cero, independiente del largo de la cuerda o la posición de las masas.

como siempre, aceleración cero no implica velocidad cero, solamente implica velocidad constante.

## unidad 03: energía y cantidad de movimiento

se hace trabajo cuando una fuerza aplicada a un cuerpo lo desplaza una cierta distancia.

el trabajo es el resultado entre el producto entre fuerza y desplazamiento y el coseno del ángulo entre la fuerza y el desplazamiento.

$$trabajo = fuerza \cdot desplazamiento \cdot cos(\theta)$$

el trabajo es un escalar, no un vector, y se mide en Joules (J). 1 Joule, es la cantidad de trabajo necesaria para ejercer una fuerza de 1 Newton en un desplazamiento de 1 metro.

$$ 1 J = 1 N \cdot 1 m$$

a su vez, podemos reemplazar la unidad de fuerza Newton por unidades de masa y aceleración, resultando en la equivalencia.

el trabajo es cero cuando:

- F = 0,si no hay fuerza, no hay trabajo
- desplazamiento = 0, si no hay desplazamiento, no hay trabajo
- ángulo = perpendicular, si el ángulo entre fuerza y desplazamiento es múltiplo de 90 grados (perpendicular), no hay trabajo.

por efecto del ángulo, tenemos que trabajo es máximo cuando el ángulo entre fuerza y desplazamiento es 0 grados, y con eso coseno de 0 grados es 1.

la potencia es la cantidad de trabajo realizada en una unidad de tiempo.

$$potencia = \frac{trabajo}{tiempo}$$

la potencia se mide en Watts (W).

$$1 W = \frac{J}{s} = \frac{kg \cdot m^2}{s^3}$$

entonces para un trabajo, mientras es realizado en menos tiempo su potencia es mayor, y viceversa.

la energía en un sistema, siempre se conserva, no se puede crear ni destruir.

a veces nuestro sistema solamente analizará un cuerpo, por ejemplo un cuerpo en caída libre. a veces considerará un cuerpo, la tierra, y a nosotros que estamos ejerciendo una fuerza sobre ese objeto, por ejemplo cuando empujamos un cuerpo.

estudiaremos 2 tipos de energía asociadas a la posición y movimiento de cuerpos puntuales de masa m:

- energía potencial: la energía en un cuerpo sólido por su posición, dependiente también de la masa y la gravedad.
- energía cinética: la energía de un cuerpo sólido por su velocidad, dependiente también de la masa.

la ecuación de energía potencial es:

$$E_p = m \cdot g \cdot h$$

donde:

- m = masa del cuerpo, en kg
- g = aceleración de gravedad, medida en metros / segundos cuadrados
- h = altura ("height" en inglés), con respecto a un sistema de referencia.

la ecuación de energía cinética es:

$$E_c = \frac{1}{2} \cdot m \cdot v^2$$

donde:

- m = masa del cuerpo, en kg.
- v = velocidad del cuerpo, en metros / segundo

como la energía en un sistema no se crea ni se destruye, solamente se transforma, podemos analizar la relación entre energía potencial y cinética en un cuerpo en caída libre. si tomamos el sistema que solamente tiene este cuerpo, y asumimos que no hay fuerzas que estén sobre ese cuerpo, sabemos que la ecuación de energía de este cuerpo de masa m, altura h y velocidad v:

$$E = E_{p} + E_{c} = m \cdot g \cdot h + \frac{1}{2} \cdot m \cdot v^2$$

si definimos nuestra altura = 0 como el suelo de la tierra, y tenemos al inicio un cuerpo a una distancia h del suelo y con velocidad nula, entonces su energía inicial está dada por:

$$E_i = E_{pi} + E_{ci} = m \cdot g \cdot h + \frac{1}{2} \cdot m \cdot 0^2 =  m \cdot g \cdot h$$

si ese cuerpo parte desde esa posición y cae en caída libre, su energía en el instante cuando choca contra el suelo es:

$$E_f = E_{pi} + E_{ci} = m \cdot g \cdot 0 + \frac{1}{2} \cdot m \cdot v^2 = \frac{1}{2} \cdot m \cdot v^2$$

y como la energía se conserva, podemos igualar:

$$E_i = E_f$$

y reemplazando:

$$m \cdot g \cdot h = \frac{1}{2} \cdot m \cdot v^2$$

y podemos dividir por m a ambos lados:

$$g \cdot h = \frac{1}{2} \cdot v^2$$

y luego multiplicar por 2 a ambos lados:

$$2 \cdot g \cdot h = \cdot v^2$$

y aplicando raíz cuadrada a ambos lados para despejar la velocidad:

$$v = \sqrt{2 \cdot g \cdot h}$$

y con esto podemos darnos cuenta que a mayor altura inicial o mayor gravedad, la velocidad final cuando se llega al suelo es mayor, y que no depende de la masa del cuerpo!

## caloría como medida de energía

en física calcularemos trabajo y energías potencial y cinética en Joule, que equivale a Newton multiplicado por metro.

una unidad de energía alternativa es una caloría (cal), que se define como la cantidad de energía necesaria para elevar en 1 grado Celsius (o Kelvin) la temperatura de un gramo de agua.

como esta cantidad es muy chica, en las tablas nutricionales de alimentos, se usa el múltiplo kilocaloría (kcal), que equivale a la energía necesaria para elevar en 1 grado Celsius (o Kelvin) la temperatura de un kilogramo de agua.

la equivalencia entre Joule y caloría está dada por:

$$1 \cdot cal = 4.184 \cdot J \approx 4 J$$

$$1 \cdot J = 0.239 \cdot cal \approx \frac{1}{4} cal$$

## unidad 04: dinámica y cinemática de cuerpo rígido

supuestos para cuerpos rígidos:

- los cuerpos tienen masa distribuida de forma constante en un volumen
- los cuerpos tienen un volumen sólido e indeformable
- aceleración de gravedad es constante en la tierra e igual a 10 metros / segundos cuadrados
- no hay atmósfera y por lo tanto, no hay roce

como nuestros cuerpos ahora no son puntos, sino que son volúmenes, pueden rotar, y podemos medir su ángulo y su velocidad angular.

$$ángulo = \theta(t)$$

ángulo lo medimos en radianes. una vuelta completa es 2 por Pi radianes, lo que equivale a 360 grados.

$$360^{\circ} = 2 \cdot \pi \cdot radianes$$

similarmente a la velocidad lineal, que es la diferencia de posición en el tiempo, la velocidad angular es la diferencia de ángulo en el tiempo y la anotamos con la letra griega omega minúscula. a su vez, la aceleración angular la anotamos con la letra griega alpha.

$$\omega(t) = \frac{\Delta \theta}{\Delta t}$$

comparemos las ecuaciones de velocidad lineal y velocidad angular.

$$v(t) = v_0 + a \cdot t$$

$$\omega(t) = \omega_0 + \alpha \cdot t$$

el torque lo anotamos con la letra griega tau.

$$\tau = torque$$

el torque es el producto entre estos 3 términos:

- r = radio o distancia entre el punto y su centro de rotación, medida en metros.
- F = fuerza externa aplicada en el punto, medida en Newton.
- sin(ángulo) = ángulo entre r y F.

y la ecuación resulta:

$$\tau = r \cdot F \cdot sin(\theta)$$

la unidad en la que se mide torque es Newton por metro, lo que simboliza fuerza aplicada sobre un radio o brazo.

a partir de la ecuación de torque, distinguimos que en estos casos el torque es nulo:

- r = 0: la distancia entre la aplicación de la fuerza y su centro de rotación es cero.
- F = 0: la fuerza aplicada es nula.
- sin(ángulo) = 0, esto ocurre cuando el ángulo es 0 o 180 grados (Pi radianes), o múltiplos.

3 aplicaciones de torque que hemos visto:

- palanca: tenemos una barra que usamos como palanca, con largo L, en la que aplicamos una fuerza con un cierto ángulo.
- puerta: la puerta tiene un ancho L, y la manilla está a distancia L de la bisagra (eje de rotación), para maximizar el torque.
- balancín: tenemos una barra de un cierto largo L, que puede girar en torno a su punto medio, y podemos hacer fuerzas a ambos lados del punto medio, para hacerlo girar, y podemos revisar hacia dónde va a girar, o si va a estar equilibrado. el largo del brazo va entre 0 y L/2.
