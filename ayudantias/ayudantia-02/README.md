# ayudantia-02

jueves 18 agosto 2022, presencial

## ejercicio-01 (30 min)

a) cuando estamos sosteniendo un cuerpo de 10 kg a 1 metro del suelo, y lo soltamos, qué fuerza le aplica la tierra a ese cuerpo, si sabemos que su aceleración es de $10 \frac{m}{s^2}$

b) si tenemos otro cuerpo de masa $m_2$ 100 kg, ubicado a 20 m del cuerpo original $m_1$, cuánta es la fuerza gravitacional que este que ejerce $m_1$ sobre $m_2$?

## solución ejercicio-01

a)

por la segunda ley de Newton, sabemos que

$$F = m \cdot a$$

reemplazando los valores:

$$F = 10 kg \cdot 10 \frac{m}{s^2} = 100 \frac{kg m}{s^2} = 100 N$$

la fuerza que le aplica la tierra es de 100N. notar que el valor de esta fuerza depende de la masa del cuerpo, y de su aceleración, en este caso la gravedad, pero no de la distancia desde donde se suelta el objeto.

b)

sabemos que por la ecuación de fuerza gravitacional universal:

$$F = G \cdot \frac{m_1 \cdot m_2}{r^2}$$

si reemplazamos con los valores de G, $m_1$, $m_2$ y $r$, obtenemos:

$$F = 6.67 \cdot 10^{-11} \frac{N \cdot m^2}{kg^2} \cdot \frac{10 kg \cdot 100 kg}{(20m)^2}$$

desarrollando las multiplicaciones:

$$F = 6.67 \cdot 10^{-11} \frac{N \cdot m^2}{kg^2} \cdot \frac{1000 kg^2}{400 m^2}$$

agrupando los números, potencias de 10 y unidades:

$$F = \frac{6.67 \cdot 1000}{400} \cdot 10^{-11} \cdot \frac{N \cdot m^2 kg^2}{kg^2}{m^2}$$

y simplificando, resulta en:

$$F = \frac{6.67}{4} \cdot 10^{-10} N \approx 1.67 \cdot 10^{-10} N$$

como vemos, esta fuerza es muy pequeña, del orden de $10^{-10}$, lo que explica a que su influencia sea muy menor, comparada con la fuerza gravitacional que ejerce la tierra sobre el cuerpo $m_1$. la gravedad nos afecta, porque los planetas son un cuerpo muy masivo, y como sabemos de la ecuación de fuerza gravitacional universal, su efecto decrece rápidamente a mayor distancia entre los cuerpos.

## ejercicio-02 (30 min)

a) cuáles son las unidades de G, la constante de gravitación universal, expresadas en función de Newton, metros y kilogramos? y expresada en función de segundos, metros y kilógramos?

b) sabiendo la magnitud de G es $6.67 \cdot 10^{-11}$ con las unidades calculadas anteriormente, calcular aproximadamente cuánto mide la gravedad en la tierra.

## solución ejercicio-02

a)

sabemos que la ecuación de gravitación universal es:

$$F = G \cdot \frac{m_1 \cdot m_2}{r^2}$$

donde $F$ se mide en Newton, $m_1$ y $m_2$ se miden en kg, y $r$ es una distancia medida en metros.

si despejamos G, nos resulta la ecuación

$$G = \frac{F \cdot r^2}{m_1 \cdot m_2}$$

y si reemplazamos las unidades, podemos ver que G se mide en:

$$G_{unidades}: \frac{N \cdot m^2}{kg^2} $$

notamos que por definición, fuerza $F$ es igual a masa $m$ por aceleración, y con eso podemos definir la equivalencia entre unidades:

$$fuerza = masa \cdot aceleración$$

$$N = kg \cdot \frac{m}{s^2}$$

y reemplazando esta equivalencia de la unidad de Newton en las unidades de G, tenemos que también podemos expresar sus unidades así:

$$G_{unidades}: N \cdot \frac{m^2}{kg^2} = \frac{kg \cdot m}{s^2} \cdot \frac{\cdot m^2}{kg^2} = \frac{m^3}{kg \cdot s^2}$$

b)

nos dan el dato que:

$$G = 6.67 \cdot 10^{-11} \frac{N \cdot m^2}{kg^2}$$

como queremos calcular la gravedad de la tierra, diremos que la tierra es un cuerpo con masa $M$, y veremos cómo atrae a un cuerpo pequeño con masa $m$, con lo que la ecuación de gravitación universal resulta:

$$F = G \frac{M \cdot m)}{r^2}$$

por la segunda ley de Newton, sabemos que la fuerza sobre un cuerpo es igual a su masa por su aceleración. si nuestro cuerpo pequeño con masa $m$ está en caída libre y solamente le afecta la fuerza de gravitación, sabemos que:

$$F = m \cdot a$$

y esa aceleración le llamamos gravedad $g$, entonces tenemos

$$F = m \cdot g$$

igualando ambas fuerzas, podemos escribir la ecuación

$$G \frac{M \cdot m)}{r^2} =  m \cdot g$$

y si despejamos g, obtenemos

$$g = \frac{G \cdot M}{r^2}$$

donde G es la constante de gravitación universal, M es la masa de la tierra, y r es el radio de la tierra.

reemplazando por valores numéricos y respetando las unidades, resulta:

$$g = \frac{6.67 \cdot 10^{-11} \frac{N m^2}{kg^2} \cdot 5.97 \cdot 10^{24} kg}{(6.37 \cdot 10^6 m)^2} $$

ordenando números, potencias de 10 y unidades de medición, tenemos:

$$g = \frac{6.67 \cdot 5.97}{6.37^2} \cdot \frac{10^{-11} \cdot 10^{24}}{(10^6)^2} \cdot \frac{N \cdot m^2 \cdot kg}{kg^2 \cdot m^2}$$

simplificando:

$$g = \frac{6.67 \cdot 5.97}{6.37^2} \cdot \frac{10^{13}}{10^12} \cdot \frac{N}{kg}$$

seguimos simplificando y reemplazamos N como el producto entre masa y aceleración:

$$g = \frac{6.67 \cdot 5.97}{6.37^2} \cdot 10 \cdot \frac{kg \cdot \frac{m}{s^2}}{kg}$$

y simplificando las unidades, tenemos

$$g = \frac{6.67 \cdot 5.97}{6.37^2} \cdot 10 \cdot \frac{m}{s^2}$$

y como el término numérico es aproximadamente igual a 1, podemos aproximar:

$$g \approx 10 \frac{m}{s^2}$$

## ejercicio-03 (30 min)

si tenemos 3 cuerpos idénticos de masa $m$, situados equidistantes, formando un triángulo equilátro de lado $r$ con ángulos interiores de 60 grados, encontrar la fuerza gravitacional total ejercida por dos de los cuerpos sobre un tercero.

pista: para simplificar los cálculos, situamos el cuerpo $m_1$ en el origen del sistema cartesiano, el cuerpo $m_2$ sobre el eje X, a distancia $r$ de $m_1$ y el tercer cuerpo $m_3$ completa el triángulo equilátero, con coordenadas x e y positivas.

## solución ejercicio-03

definimos la fuerza gravitacional total sobre el cuerpo $m_1$ como $F_1$, y sabemos que es el resultado de las otras dos fuerzas presentes: $F_{2,1}$ y $F_{3,1}$, que son la fuerza que ejerce el cuerpo $m_2$ sobre $m_1$, y la que ejerce el cuerpo $m_3$ sobre $m_1$, respectivamente.

$$\vec{F_1} = \vec{F_{2,1}} + \vec{F_{3,1}}$$

calculemos primero la magnitud de $F_{2,1}$:

$$F_{2,1} = G \cdot \frac{m_1 \cdot m_2}{r^2} = G \cdot \frac{m^2}{r^2}$$

sabemos que el cuerpo 2 atrae al cuerpo 1 hacia la derecha, por lo que la dirección es $\hat{x}$. entonces para calcular el vector de la fuerza $\vec{F_{2,1}}$, reemplazamos:

$$\vec{F_{2,1}} = F_{2,1} \cdot \hat{x} = G \cdot \frac{m^2}{r^2} \cdot \hat{x}$$

ahora calculemos la magnitud de $F_{3,1}$:

$$F_{3,1} = G \cdot \frac{m_1 \cdot m_3}{r^2} = G \cdot \frac{m^2}{r^2}$$

notamos que la magnitud $F_{3,1}$ es igual a $F_{2,1}$, lo que tiene sentido, ya que las distancias son las mismas, y las masas son también las mismas!

para calcular el vector $\vec{F_{3,1}}$, notamos que la masa $m_3$ atrae hacia sí la masa $m_1$, por lo que la dirección será en dirección hacia arriba y la derecha en el plano cartesiano.

si hacemos el triángulo rectángulo entre la posición de la masa $m_1$ en el origen (0, 0) y la posición (x, y) de la masa $m_3$, vemos que x e y son los catetos y r es la hipotenusa, y que el ángulo interno es de 60 grados, así que podemos plantear el sistema de 2 ecuaciones y 2 incógnitas:

$$ sin(60 grados) = \frac{cateto opuesto}{hipotenusa} \brack cos(60 grados) = \frac{cateto adyacente}{hipotenusa}$$

reemplazando con los datos:

$$ sin(60 grados) = \frac{y}{r} \brack cos(60 grados) = \frac{x}{r}$$

despejando x e y:

$$ x = r \cdot cos(60 grados) \brack y = r \cdot sin(60 grados)$$

y reemplazando los valores de seno y coseno:

$$ x = r \cdot \frac{1}{2} \brack y = r \cdot \frac{\sqrt{3}}{2}$$

y con eso tenemos que el vector $\vec{r_{1, 3}}$ que va de $m_1$ a $m_3$ es:

$$\vec{r_{1, 3}} = r \cdot \frac{1}{2} \cdot \hat{x} + r \cdot \frac{\sqrt{3}}{2} \cdot \hat{y}$$

pero necesitamos el vector unitario de ese vector, que se puede obtener al dividir cualquier vector por su módulo, con esta fórmula:

$$\hat{A} = \frac{\vec{A}}{|\vec{A}|}$$

y con eso, calculemos el vector unitario $\hat{r\_{1, 3}}$

$$\hat{r\_{1, 3}} = \frac{\vec{r_{1, 3}}}{|\vec{r_{1, 3}}|} = \frac{r \cdot \frac{1}{2} \cdot \hat{x} + r \cdot \frac{\sqrt{3}}{2} \cdot \hat{y}}{r}$$

y despejando, resulta:

$$\hat{r\_{1, 3}} = = \frac{1}{2} \cdot \hat{x} + \frac{\sqrt{3}}{2} \cdot \hat{y}$$

y ahora sí podemos encontrar el vector $\vec{F_{3, 1}}$:

$$\vec{F_{3,1}} = F{3,1} \cdot \hat{r\_{1, 3}}$$

y reemplazando:

$$\vec{F_{3,1}} = G \cdot \frac{m^2}{r^2} \cdot (\frac{1}{2} \cdot \hat{x} + \frac{\sqrt{3}}{2} \cdot \hat{y})$$
