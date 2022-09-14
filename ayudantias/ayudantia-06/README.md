# ayudantia-06

unidad 4: dinámica y cinemática de cuerpo rígido

## ejercicio-01: torque en puerta (30 minutos)

a) si tenemos una puerta, con un ancho de 1 metro, y queremos realizar un torque de 20 Nm en la manilla de la puerta, determinar la fuerza necesaria para obtener ese torque al aplicar la fuerza de forma perpendicular.

b) con la misma fuerza calculada en a), cuánto es el torque si la puerta tiene el doble de masa? y si la manilla está en la mitad de la puerta? y si la manilla está al lado de la bisagra?

## solución ejercicio-01

a)

la ecuación de torque es:

$$\tau = r \cdot F \cdot sin(\theta)$$

tenemos que del enunciado, los valores son:

- tau = 20 Nm
- r = 1m, asumiendo que la manilla está en el lado opuesto de la bisagra de la puerta, donde rota.
- ángulo = 90 grados.

$$20 \cdot N \cdot m = 1 \cdot m \cdot F \cdot sin(90^{\circ})$$

podemos dividir por m, y reemplazar sin(90 grados) por 1:

$$20 \cdot N = F $$

y llegamos a la respuesta que la fuerza de 20 N es la necesaria para generar un torque de 20 Nm, al ser aplicada de forma perpendicular en la manilla de la puerta.

b)

de la ecuación de torque, vemos que no depende de la masa de la puerta, por lo tanto el torque se mantiene igual, independiente de la masa de la puerta, por lo que el torque_2 es igual al torque original.

$$\tau_2 = 1 m \cdot 20 N \cdot sin(90^{\circ}) = 20 \cdot N \cdot m = \tau$$

si la manilla está a la mitad, la distancia r ahora es 0.5 m, y con eso el torque_3 resulta la mitad del torque original, según la ecuación:

$$\tau_3 = 0.5 m \cdot 20 N \cdot sin(90^{\circ}) = 10 \cdot N \cdot m = \frac{1}{2} \cdot \tau$$

si la manilla está justo a la bisagra, ahora la distancia r es 0 m, con lo que el torque es nulo, según la ecuación:

$$\tau_4 = 0 m \cdot 20 N \cdot sin(90^{\circ}) = 0 \cdot N \cdot m$$

## ejercicio-02: torque en palanca (30 minutos)

a) si tenemos una fuerza de 100 N, y la aplicamos a una palanca en ángulo de 30 grados, cuánto tiene que medir la palanca para ejercer un torque de 1500 Nm?

b) encontrar otros 2 casos que producen el mismo torque con la misma fuerza que en a). especifique las distancias r_1, r_2 y los correspondientes ángulos theta_1 y theta_2.

## solución ejercicio-02

a)

la ecuación de torque es:

$$\tau = r \cdot F \cdot sin(\theta)$$

tenemos que del enunciado, los valores son:

- fuerza = 100 N
- tau = 1500 Nm
- ángulo = 30 grados
- sin(ángulo) = sin(30 grados) = 0.5

$$1500 \cdot N \cdot m = X \cdot 100 \cdot N \cdot sin(30^{\circ})$$

si dividimos por 100N y reemplazamos sin(30 grados) por 0.5

$$15 \cdot= X \cdot \frac{1}{2}$$

y si multiplicamos por 2, despejamos X:

$$X = 30 m$$

entonces la palanca debe medir 30 m, para ejercer un torque de 1500 Nm, al aplicársele una fuerza de 100 N en un ángulo de 30 grados.

b)

en la ecuación de torque tenemos:

$$\tau = r \cdot F \cdot sin(\theta)$$

y nos dicen el valor del torque y de la fuerza, entonces:

$$1500 \cdot N \cdot m = r \cdot 100 \cdot N \cdot sin(\theta)$$

y diviendo por 100 N tenemos la relación entre r y theta:

$$15 \cdot m = r \cdot sin(\theta)$$

y nos piden dos pares de distancia r y ángulo theta que cumplan con estas condiciones.

podemos definir un ángulo como 60 grados y despejar su distancia r:

$$15 \cdot m = r_2 \cdot sin(60^{\circ})$$

y con esto:

$$r_2 = \frac{15 \cdot m}{sin(60^{\circ})} = \frac{15 \cdot m}{\frac{\sqrt(3)}{2}} = \frac{30 \cdot m}{\sqrt(3)}$$

y aproximadamante:

$$r_2 \approx 17.32 m$$

podemos definir el otro ángulo como 90 grados y despejar su r:

$$15 \cdot m = r_3 \cdot sin(90^{\circ})$$

y como sin(90 grados) es 1:

$$r_3 = 15 \cdot m = r_3$$

y una respuesta posible entonces es que con la misma fuerza F , podemos generar el mismo torque tau, aplicando la fuerza en estos 2 lugares y ángulo:

- radio de 17.32 m y ángulo de 60 grados
- radio de 15 m y ángulo de 90 grados

esto cumple con nuestras expectativas, que con el mismo torque y fuerza, a mayor radio tenemos tenemos menor ángulo y viceversa.

otras respuestas posibles incluyen definir la distancia como 20 m, y reemplazar:

$$15 \cdot m = 20 m \cdot sin(\theta_4)$$

y con esto, despejar sin(ángulo) así:

$$sin(\theta_4) = \frac{15}{20} = \frac{3}{4}$$

y despejar sin() con la función opuesta, arcsin():

$$\theta_4 = arcsin(\frac{3}{4}) = 48.59^{\circ}$$

y también podemos reemplazar la distancia como 25 m y obtener otro valor de ángulo:

$$15 \cdot m = 25 m \cdot sin(\theta_5)$$

y despejar sin(ángulo):

$$sin(\theta_5) = \frac{15}{25} = \frac{1}{5}$

y despejar sin() con la función opuesta arcsin():

$$\theta_5 = arcsin(\frac{1}{5}) = 11.54^{\circ}$$

y tener otro resultado posible:

- radio de 20 m y ángulo de 48.59 grados
- radio de 25 m y ángulo de 11.54 grados

lo que también confirma que a igual torque y fuerza, tenemos una relación inversa entre radio y ángulo: a menor radio, mayor ángulo, y viceversa.

## ejercicio-03: torque en balancín (30 minutos)

a) en un balancín de largo 3m, con su eje de rotación al medio, determinar el torque hecho por una fuerza de 30N de forma perpendicular, a medio metro del eje de rotación.

b) determinar en qué posición al otro lado del balancín podemos usar una fuerza perpendicular de 10 N para tener el balancín en equilibrio? y si la fuerza es perpendicular y de 20N?

## solución ejercicio-03

a)

usamos la ecuación de torque:

$$\tau_1 = r \cdot F \cdot sin(\theta)$$

y sabemos los siguientes datos:

- F = 30 N
- r = 0.5 m
- sin(90 grados) = 1

podemos reemplazar:

$$\tau_1 = 0.5 \cdot m \cdot 30 \cdot N \cdot sin(90)$$

y despejar:

$$\tau_1 = 15 \cdot N \cdot m$$

b)

para que el balancín esté en equilibrio, al otro lado debemos tener el mismo torque, entonces la ecuación queda:

$$15 \cdot N \cdot m = X \cdot F \cdot sin(90) = X \cdot F$$

entonces, para la fuerza de 10N, tenemos:

$$15 \cdot N \cdot m = X_{10} \cdot 10 \cdot N$$

y dividiendo por 10 N, despejamos X:

$$X_{10} = \frac{15}{10} \cdot  m = 1.5 m$$

para el caso de la fuerza de 20N, tenemos:

$$15 \cdot N \cdot m = X_{20} \cdot 20 \cdot N$$

y dividiendo por 20 N, despejamos X:

$$X_{20} = \frac{15}{20} \cdot m = 0.75 m$$

entonces resumiendo:

para mantener al balancín en equilibrio podemos usar 1 de estas 2 fuerzas perpendiculares:

- Fuerza de 10 N a 1.5 m del centro de rotación, o sea, en el extremo del balancín de 3m.
- Fuerza de 20 N a 0.75m del centro de rotación, o sea, a la mitad del lado del balancín de 3m.
