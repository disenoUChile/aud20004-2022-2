# clase-10

martes 18 octubre 2022, en línea y asíncrona

repaso para control 02:

- unidad 5: calor y temperatura
- unidad 6: ondas y sonido

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

## expansión térmica

$$\Delta L = \alpha \cdot L_0 \cdot \Delta T$$

$$\Delta A = 2 \cdot \alpha \cdot A_0 \cdot \Delta T = \beta \cdot A_0 \cdot \Delta T$$

$$\Delta V = 3 \cdot \alpha \cdot V_0 \cdot \Delta T = \gamma \cdot V_0 \cdot \Delta T$$

## definición de onda

cuando grafiquemos ondas, vamos a tener 2 gráficos:

- gráfico de amplitud de la onda en el tiempo, lo que implica que el punto en el espacio está fijo, aquí el eje horizontal de la variable independiente es TIEMPO.

- gráfico de amplitud de la onda en el espacio, lo que implica que el tiempo está fijo o detenido, aquí el eje horizontal de la variable independiente es ESPACIO.

ojo con los ejes!!

## parámetros de las ondas sinusoidales

una onda sinusoidal se puede definir por estas tres características:

- amplitud (A): distancia entre el punto de equilibrio y el desplazamiento máximo, se mide en metros.
- periodo (T): tiempo que demora la onda en repetirse, se mide en segundos.
- frecuencia (f): inverso del periodo, se mide en Hz.

## longitud de onda

- longitud de onda (lambda): distancia entre repeticiones de la onda, se mide en metros.

$$lambda = \lambda$$

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
