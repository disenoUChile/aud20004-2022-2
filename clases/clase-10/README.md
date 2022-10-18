# clase-10

martes 18 octubre 2022, en línea y asíncrona

unidad 5: calor y temperatura

## repaso clase anterior y programa hoy (15 min)

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

la constante de los gases universales, la denotamos por R y tiene el valor:

$$R = 9.31 \frac{J}{mol K}$$

la ecuación de los gases ideales es:

$$P \cdot V =  n \cdot R \cdot T$$

## unidades de medida en gases ideales

expresamos la temperatura T en Kelvin, abreviado K. una diferencia de 1 grado Celsius es igual a 1 grado Kelvin.

$$\Delta T_{Celsius} = \Delta T_{Kelvin}$$

$$K = C + 273$$

$$C = K - 273$$

la presión la medimos en Pascales (Pa), que equivale a

$$ Pa = \frac{N}{m^2}$$

un valor típico de presión, es la presión atmosférica al nivel del mar:

$$presión_{atmosférica} \approx 100 kPa$$

## condiciones estándar en gases ideales

diremos que las condiciones estándar para un gas ideal son:

- presión = 1 atmósfera = 100 kPa
- temperatura = 0 Celsius = 273 Kelvin

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

diremos que el calor es la energía total que tiene un cuerpo debido al movimiento de sus partículas, y que puede ser transferido a otro cuerpo, mientras que la temperatura es un resumen de ese movimiento promedio.

$$C = \frac{5}{9} (F - 32}$$

## expansión térmica

$$\Delta L = \alpha \cdot L_0 \cdot \Delta T$$

$$\Delta A = 2 \cdot \alpha \cdot A_0 \cdot \Delta T = \beta \cdot A_0 \cdot \Delta T$$

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

## definición de onda

cuando grafiquemos ondas, vamos a tener 2 gráficos:

- gráfico de amplitud de la onda en el tiempo, lo que implica que el punto en el espacio está fijo, aquí el eje horizontal de la variable independiente es TIEMPO.

- gráfico de amplitud de la onda en el espacio, lo que implica que el tiempo está fijo o detenido, aquí el eje horizontal de la variable independiente es ESPACIO.

ojo con los ejes!!

## análisis de Fourier

Fourier postuló que toda onda se puede expresar como una suma de ondas sinusoidales.

esto es genial, porque las sinusoides se identifican con 3 datos:

1. amplitud, se mide en metros.
2. frecuencia, se mide en Hz.
3. fase, se mide en radianes.

entonces, si tenemos una máquina que es capaz de crear ondas sinusoidales y sumarlas, podemos crear cualquier onda, por ejemplo, cualquier sonido.

por eso, en ciencias tendemos a analizar las señales y ondas en función de las sinusoides que los conforman.

un nombre de esta técnica que encuentran en computación es FFT, que significa Fast Fourier Transform.

## parámetros de las ondas sinusoidales

una onda sinusoidal se puede definir por estas tres características:

- amplitud (A): distancia entre el punto de equilibrio y el desplazamiento máximo, se mide en metros.
- periodo (T): tiempo que demora la onda en repetirse, se mide en segundos.
- frecuencia (f): inverso del periodo, se mide en Hz.

## longitud de onda

- longitud de onda (lambda): distancia entre repeticiones de la onda, se mide en metros.

$$lambda = \lambda$$

## definición de sonido

el sonido es una onda producida por un cuerpo en vibración.

la vibración comprime y descomprime el aire alrededor, lo que genera una onda longitudinal.

las moléculas de aire oscilan de forma paralela a la dirección del movimiento de la onda, recibiendo energía de moléculas adyacentes.

el otro tipo de onda es transversal, donde las moléculas se mueven de forma perpendicular al movimiento de la onda.

## relaciones entre mundo físico y perceptual

- la amplitud de una onda de sonido la percibimos como volumen.
- la frecuencia de una onda de sonido la percibimos como altura.
- la fase de una onda no produce un cambio perceptual.

## velocidad del sonido

a 20 Celsius, la velocidad del sonido es de 343 metros por segundo, y es la velocidad que usaremos en este curso.

$$v_{sonido} = 343 \cdot \frac{m}{s}$$

la ecuación que relaciona la velocidad, longitud y frecuencia de una onda es:

$$v_{sonido} = \lambda \cdot f_{sonido}$$

entonces podemos calcular la longitud de onda de cualquier onda si sabemos su frecuencia.

## efecto Doppler

$$f = f_{original} \cdot \frac{v_{sonido} \mp v_{receptor}}{v_{sonido} \mp v_{fuente}}$$

## primer paso para digitalizar: muestrear

teorema de Nyquist:

$$f_{muestreo} > 2 \cdot f_{máxima}$$

en palabras, para cualquier onda, la frecuencia de muestreo para digitalizar esa onda debe ser estrictamente mayor que el doble de la frecuencia máxima de la onda.

## segundo paso para digitalizar: cuantizar

debemos truncar ese valor a una cierta resolución, esto recibe el nombre de cuantización.

para cuantizar debemos decidir cuántos bits de resolución usaremos, y eso está sujeto tanto a nuestra percepción como a la capacidad de la tecnología y su costo.

el número de bits (B) determina cuántos pasos tenemos para la resolución de una onda digital.

$$pasos = 2^B$$

por ejemplo, en la tecnología de audio digital para CDs, se decidió en una resolución de 16 bits, con lo que para CDs:

$$pasos_{16 bits} = 2^{16} = 65536$$
