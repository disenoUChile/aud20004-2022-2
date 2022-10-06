# ayudantia-08

jueves 06 octubre 2022, presencial

## ejercicio-01: gas ideal (30 min)

a) si un gas está en un contenedor de 30 litros a presión atmosférica, cuál será su presión si el volumen aumenta a 100 litros, y la temperatura se mantiene constante a 30 Celsius?

b) tras este cambio de presión y volumen, mantenemos constante la presión y subimos la temperatura de 30 Celsius a 100 Celsius, cuál es el nuevo volumen?

## solución ejercicio-01

a)

como la temperatura es constante, podemos usar la ecuación que relaciona presión y volumen de la siguiente forma:

$$P \cdot V = constante$$

primero expresemos la presión original en Pascales

$$P_1 = 1 atm = 100 kPa$$

y luego el volumen original en metros cúbicos:

$$V_1 = 30 litros = 30 (dm)^3 = 30 (\frac{1}{10} m)^3 = \frac{30}{1000} m^3 = 3 \cdot 10^{-2} \cdot m^3$$

ahora expresemos el nuevo volumen en metros cúbicos:

$$V_2 = 100 litros = 100 (dm)^3 = 100 (\frac{1}{10} m)^3 = \frac{100}{1000} m^3 = 10^{-1} \cdot m^3$$

ahora podemos plantear la ecuación:

$$P_1 \cdot V_1 = P_2 \cdot V_2$$

y despejando la nueva presión:

$$P_2 = \frac{P_1 \cdot V_1}{V_2}$$

y reemplazando los valores:

$$P_2 = \frac{100 kPa \cdot 3 \cdot 10^{-2} \cdot m^3}{10^{-1} \cdot m^3}$$

$$P_2 = 30 kPa$$

y simplificando:

$$P_2 = \frac{100 kPa \cdot 3 \cdot 10^{-2}}{10^{-1}} = \frac{3 kPa}{10^{-1}} = 30 kPa$$

ya que presión y volumen son inversamente proporcionales, en este caso el volumen aumentó, y entonces la presión disminuyó, y su nuevo valor es de 30 kPa.

b)

sabemos que si la presión se mantiene constante, el volumen y la temperatura de un gas ideal son inversamente proporcionales, así que usaremos esta ecuación.

$$\frac{V}{T} = constante$$

en esta ecuación, tenemos las siguientes condiciones iniciales:

$$V_2 = 100 litros = 10^{-1} \cdot m^3$$

$$T_2 = 30 Celsius = 30 + 273 K = 303 K$$

y por el enunciado nos dice que la nueva temperatura es:

$$T_3 = 100 Celsius = 100 + 273 K = 373 K$$

encontremos el nuevo volumen según esta igualdad:

$$\frac{V_2}{T_2} = \frac{V_3}{T_3}$$

despejamos V_3:

$$V_3 = V_2 /cdot \frac{T_3}{T_2}$$

reemplazamos los valores:

$$V_3 = 10^{-1} \cdot m^3 /cdot \frac{373 K}{303 K}$$

$$V_3 = 1.23 \cdot 10^{-1} \cdot m^3$$

en este caso tenemos que la presión se mantiene constante, y como la temperatura sube, el volumen también sube.

## ejercicio-02: transferencia de calor

a)

$$Q = m \cdot c \cdot \Delta T$$

b)

## solución ejercicio-02

## ejercicio-03

## solución ejercicio-03

# clase-08

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

las leyes de la termodinámica involucran a las relaciones entre calor y energía mecánica, eléctrica, entre otras. son válidas solamente en sistemas en equilibrio, no en sistemas en procesos de cambios muy rápidos o de transiciones complejas.

la primera ley de la termodinámica tiene que ver con la ley de la conservación de la energía y dice así:

$$\Delta Q = \Delta U + \Delta W$$

donde:

- Delta Q: energía de calor de entrada al sistema
- Delta U: cambio de energía interna del sistema
- Delta W: trabajo hecho por el sistema

existen muchos corolarios que podemos decir, como por ejemplo:

- si la energía del sistema sube, puede ser porque entra energía al sistema, o porque se hace trabajo sobre el sistema.
- si no ingresa energía en forma calor al sistema, todo el cambio de energía del sistema está dado por el trabajo realizado por el sistema.

la segunda ley de la termodinámica postula que es imposible construir una máquina que absorbiendo calor de una fuente de calor, haga un trabajo que sea 100% eficiente, ya que siempre pierde calor con el ambiente.

otra manera de ver la segunda ley es que el calor no fluye espontáneamente de un cuerpo a otro cuerpo con mayor temperatura.

de hecho, hay un concepto de entropía S, cuya fórmula es

$$\Delta S = \frac{\Delta Q}{T}$$

el cambio de entropía en un sistema es igual al calor que fluye hacia el sistema, dividido por la temperatura en grados Kelvin.

la entropía del universo aumenta o permanece constante, pero nunca baja. quizás un sistema puede bajar localmente su entropía, pero para eso está en contacto con otros sistemas cuya entropía sube, y el neteo es cero o mayor que cero.

los cuerpos están constantemente compartiendo calor, y con eso sus temperaturas tienden a equilibrarse, y eventualmente el universo estará a la misma temperatura, y no habrá energía disponible para ser usada.

## temperatura

la temperatura es una propiedad física que tienen los cuerpos, que mide la energía cinética promedio de sus moléculas, por lo tanto, no depende de su masa. esto es una gran diferencia con calor, que sí depende de la masa o cantidad de materia.

diremos que el calor es la energía total que tiene un cuerpo debido al movimiento de sus partículas, y que puede ser transferido a otro cuerpo, mientras que la temperatura es un resumen de ese movimiento promedio.

existen distintas escalas para medir temperatura.

la escala Celsius tiene estos dos puntos importantes:

- 0 Celsius = congelamiento del agua a presión atmosférica
- 100 Celsisus = ebullición del agua a presión atmosférica

la escala Kelvin tiene estos hitos:

- 0 Fahrenheit = temperatura de una mezcla de agua, sal y una sal
- 96 grados Fahrenheit = temperatura corporal normal

esto lleva a que:

$$C = \frac{5}{9} (F - 32}$$

$$-40 C = -40 F$$

nosotros en este curso usaremos Kelvin, cuyo grado mide lo mismo que Celsius, solamente se distinguen en su punto de referencia.

## expansión térmica

usaremos la letra alpha para definir el coeficiente promedio de expansión lineal, que se mide en 1 / Celsius, y nos permite expresar la expansión en una dimensión con la ecuación:

$$\Delta L = \alpha \cdot L_0 \cdot \Delta T$$

el coeficiente de expansión de área lo denotamos por la letra griega beta y equivale a 2 veces alpha, entonces:

$$\Delta A = 2 \cdot \alpha \cdot A_0 \cdot \Delta T = \beta \cdot A_0 \cdot \Delta T$$

de forma similar con el volumen, usamos la letra griega gamma,y equivale a 3 alpha

$$\Delta V = 3 \cdot \alpha \cdot V_0 \cdot \Delta T = \gamma \cdot V_0 \cdot \Delta T$$

ejemplo:

si tenemos un área de 10 milímetros cuadrados en un metal con alpha de 1.1 por 10 elevado a -5. si aumentamos su temperatura de 20 Celsius a 70 Celsius, calcular la diferencia de área producida.

primero, tenemos la noción de que la temperatura cuando sube, los cuerpos se expanden.

veamos la fórmula:

$$\Delta A = 2 \cdot \alpha \cdot A_0 \cdot \Delta T$$

reemplacemos los valores:

$$\Delta A = 2 \cdot 1.1 \cdot 10^{-5} \cdot  \frac{1}{C} \cdot 10 mm^2 \cdot (70 C - 20 C)$$

desarollando:

$$\Delta A = 2 \cdot 50 \cdot 1.1 \cdot 10 \cdot 10^{-5}  mm^2$$

$$\Delta A = 1.1  \cdot 10^{-2}  mm^2$$

$$\Delta A = 0.011 mm^2$$

esto es la diferencia de área, por lo que el área nueva será área original + Delta área, o sea:

$$A_{nueva} = A_{original} + \Delta A = 10 mm^2 + 0.011 mm^2 = 10.011 mm^2$$

## bibliografía

- https://www.cliffsnotes.com/study-guides/physics/thermodynamics/development-of-the-ideal-gas-law
- https://www.youtube.com/watch?v=En3bRCuLQZM
