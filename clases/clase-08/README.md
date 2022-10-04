# clase-08

martes 04 octubre 2022, presencial

unidad 5: calor y temperatura

## repaso clase anterior y programa hoy (15 min)

la clase anterior vimos la unidad 4: dinámica y cinemática de cuerpo rígido

- supuestos para cuerpos puntuales
- supuestos para cuerpos rígidos
- movimiento angular
- torque
- torques nulos
- aplicaciones de torque: puerta y manilla
- aplicaciones de torque: palanca
- aplicaciones de torque: balancín

la clase de hoy es la unidad 5: calor y temperatura

- gases ideales
- unidades de medida en gases ideales
- condiciones estándar en gases ideales
- calor
- transferencia de calor
- leyes de la termodinámica
- temperatura
- expansión térmica

## gases ideales

un gas ideal es una abstracción, que postula que un gas consiste de partículas idénticas, infinitesimalmente pequeñas y que interactúan solamente ocasionalmente, de forma elástica.

los gases reales en nuestro planeta actúan de forma muy parecida a los gases ideales, pero esto no aplica a otros gases en otras condiciones, como los gases en el sol, que tienen altísimas temperaturas y presiones.

en un gas ideal, su presión P, volumen V, y cantidad están relacionadas por leyes postuladas por físiques entre los siglos 17 y 19 dC, incluyendo a Robert Boyle, Jacques Charles y Joseph Gay-Lussac. estas leyes condensan el resultado de experimentos y observaciones.

la ley de Boyle dice que la presión y el volumen de un gas ideal son inversamente proporcionales. lo que equivale a decir que la multiplicación de presión por volumen es constante.

$$P \cdot V = constante$$

la ley de Charles/Gay-Lussac dice que a presión constante, el volumen de un gas es directamente proporcional a su temperatura.

$$\frac{V}{T} = constante$$

también sabemos que el volumen de un gas es directamente proporcional a su masa, por lo que tenemos la ecuación:

$$\frac{V}{m} = constante$$

si combinamos estas tres ecuaciones, podemos escribir:

$$P \cdot V = constante \cdot m \cdot T$$

Amadeo Avogadro postuló que un mol de cualquier gas a presión y temperatura estándar contiene el mismo número de moléculas. Esta cantidad se llama número de Avogradro y su fórmula es:

$$número_{Avogadro} = 6.02 \cdot 10^{23} \frac{moléculas}{mol}$$

esta ecuación es válida para todos los gases, y para simplificar los cálculos, podemos definir la cantidad de gas como una medida en moles, en vez de masa.

el número de moles "n" de un gas es la razón entre la masa "m" y su masa atómica "M" expresada en gramos por mol.

$$n = \frac{m}{M}$$

con esto, la ecuación resulta

$$P \cdot V = constante \cdot n \cdot T$$

y la constante recibe el nombre de constante de los gases universales, la denotamos por R y tiene el valor:

$$R = 9.31 \frac{J}{mol K}$$

## unidades de medida en gases ideales

expresamos la temperatura T en Kelvin, abreviado K. una diferencia de 1 grado Celsius es igual a 1 grado Kelvin.

$$\Delta T_{Celsius} = \Delta T_{Kelvin}$$

la gran diferencia entre grados Celsius y Kelvin, es dónde está el cero, origen, o referencia. en grados Celsius, 0 grados equivale al punto de congelación del agua a la presión atmósferica del nivel del mar.

en cambio, 0 grados Kelvin, equivale al cero absoluto, a la menor temperatura posible, y equivale a 273.15 grados Celsius.

$$0 K = -273.15 C$$

entonces podemos convertir con las siguiente fórmulas equivalentes, donde omitimos los decimales para simplificar los cálculos.

$$K = C + 273$$

$$C = K - 273$$

la presión la medimos en Pascales (Pa), que equivale a

$$ Pa = \frac{N}{m^2}$$

un valor típico de presión, es la presión atmosférica al nivel del mar:

$$presión_{atmosférica} \approx 100 kPa$$

eso se explica porque si tomamos una columna de aire que va desde el nivel del mar hasta el borde de la atmósfera, su masa es alrededor de un kilo, y por lo tanto, su peso, alrededor de 10 N.

con esto, la presión es:

$$presión_{atmosférica} \approx \frac{100 N}{1 cm^2} \approx \frac{100 N}{1 (\frac{m}{100})^2} \approx \frac{100^3 N}{1 m^2} = 100 kPa$$

el volumen lo medimos en m^3

## condiciones estándar en gases ideales

diremos que las condiciones estándar para un gas ideal son:

- presión = 1 atmósfera = 10 kPa
- temperatura = 0 Celsius = 273 Kelvin

con esto, podemos demostrar que el volumen de un gas en estas condiciones es aproximadamente 25 litros.

## calor

calor y temperatura son cantidades físicas distintas.

si dos objetos de distintas temperaturas están en contacto con el otro, fluye calor desde el cuerpo con mayor temperatura hacia el cuerpo con menor temperatura.

el calor es una medida de energía.

todos los cuerpos tienen una capacidad calórica, que es la cantidad necesaria de calor necesaria para elevar la temperatura de un objeto en un grado (Celsius o Kelvin).

## transferencia de calor

la ecuación de transferencia de calor postula que el la transferencia de calor Q de un cuerpo está dada por el producto entre su masa, su capacidad calórica específica, y la diferencia de temperatura.

$$Q = m \cdot c \cdot \Delta T$$

las unidades son:

- Q: calor (J)
- m: masa, (kg)
- c: capacidad calórica específica (J/(kg K))
- T: temperatura (K)

por ejemplo, si tenemos un bloque de metal con cierta alta temperatura, y lo depositamos en una masa de agua con menor temperatura. si la temperatura final es T, cómo se relacionan los calores específicos?

$$Q{metal} = m_{metal} \cdot c_{metal} \cdot \Delta T_{metal} = m_{metal} \cdot c_{metal} \cdot (T_{final} - T_{metal inicial})$$

$$Q{agua} = m_{agua} \cdot c_{agua} \cdot \Delta T_{agua} = m_{agua} \cdot c_{agua} \cdot (T_{final} - T_{agua inicial})$$

y si el sistema está aislado:

$$Q_{metal} + Q_{agua} = 0$$

$$m_{metal} \cdot c_{metal} \cdot (T_{final} - T_{metal inicial}) + m_{agua} \cdot c_{agua} \cdot (T_{final} - T_{agua inicial}) = 0$$

en esta ecuación tenemos datos, como la masa de los cuerpos, su calor específico, y sus temperaturas iniciales, y con eso podemos encontrar T, y es el tipo de ejercicio que veremos en ayudantía.

## leyes de la termodinámica

la segunda ley de la termodinámica postula que es imposible construir una máquina que absorbiendo calor de una fuente de calor, haga un trabajo que sea 100% eficiente, ya que siempre pierde calor con el ambiente.

otra manera de ver la segunda ley es que el calor no fluye espontáneamente de un cuerpo a otro cuerpo con mayor temperatura.

## temperatura

## expansión térmica

usaremos la letra alpha para definir el coeficiente promedio de expansión lineal, que se mide en 1 / Celsius, y nos permite expresar la expansión en una dimensión con la ecuación:

$$\Delta L = \alpha \cdot L_0 \cdot \Delta T$$

el coeficiente de expansión de área lo denotamos por la letra griega beta y equivale a 2 veces alpha, entonces:

$$\Delta A = 2 \cdot \alpha \cdot A_0 \cdot \Delta T = \beta \cdot A_0 \cdot \Delta T$$

de forma similar con el volumen, usamos la letra griega gamma,y equivale a 3 alpha

$$\Delta V = 3 \cdot \alpha \cdot V_0 \cdot \Delta T = \gamma \cdot V_0 \cdot \Delta T$$

ejemplo:

si tenemos

## bibliografía

- https://www.cliffsnotes.com/study-guides/physics/thermodynamics/development-of-the-ideal-gas-law
