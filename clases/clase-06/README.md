# clase-06

martes 20 septiembre 2022, presencial

unidad 4: dinámica y cinemática de cuerpo rígido

## repaso clase anterior y programa hoy (15 min)

la clase anterior vimos la unidad 3: energía y cantidad de movimiento

- definición de trabajo
- cálculo de trabajo
- definición de energía
- definición de potencia
- conservación de energía

la clase de hoy es la unidad unidad unidad 4: dinámica y cinemática de cuerpo rígido

## supuestos hasta el momento

hasta ahora, en cinemática, dinámica, energía y trabajo, hemos utilizado los siguientes supuestos:

- los cuerpos no tienen volumen
- los cuerpos pueden ser resumidos como su posición en el espacio, y su masa.
- aceleración de gravedad es constante en la tierra e igual a 10 metros / segundos cuadrados.
- no hay atmósfera y por lo tanto, no hay roce.

## supuestos para cuerpos rígidos

- definición de cuerpo rígido: un cuerpo rígido tiene una masa constante y un volumen sólido e indeformable.

## movimiento angular

como nuestros cuerpos ahora no son puntos, sino que son volúmenes, pueden rotar.

en vez de medir su desplazamiento lineal como una distancia metros, vamos a medir su desplazamiento angular en radianes.

una vuelta completa es 360 grados, lo que equivale a 2 por Pi radianes.

$$360^{\circ} = 2 \cdot \pi \cdot radianes$$

$$ángulo = \theta(t)$$

similarmente a la velocidad lineal, que es la diferencia de posición en el tiempo, la velocidad angular es la diferencia de posición angular en el tiempo y la anotamos con la letra griega omega minúscula.

$$\omega(t) = \frac{\Delta \theta}{\Delta t}$$

comparemos las ecuaciones de velocidad lineal y velocidad angular:

$$v(t) = v_0 + a \cdot t$$

$$\omega(t) = \omega_0 + \alpha \cdot t$$

notar que aceleración angular la anotamos con la letra griega alpha.

## torque

el torque lo anotamos con la letra griega tau.

$$\tau = torque$$

el torque es el producto entre estos 3 términos:

- r = radio o distancia entre el punto y su centro de rotación, medida en metros.
- F = fuerza aplicada en el punto, medida en Newton.
- sin(ángulo) = ángulo entre r y F.

y la ecuación resulta:

$$\tau = r \cdot F \cdot sin(\theta)$$

la unidad en la que se mide torque es Newton por metro, lo que simboliza fuerza aplicada sobre un radio o brazo.

veamos los casos extremos cuando el torque es nulo (cero).

## torques nulos

a partir de la ecuación de torque

$$\tau = r \cdot F \cdot sin(\theta)$$

distinguimos que en estos casos el torque es nulo:

- r = 0: la distancia entre la aplicación de la fuerza y su centro de rotación es cero.
- F = 0: la fuerza aplicada es nula.
- sin(ángulo) = 0, esto ocurre cuando el ángulo es 0 o 180 grados (Pi radianes), o múltiplos.

## aplicaciones de torque: puerta y manilla

por qué la manilla de la puerta está en el extremo opuesto al centro de rotación?

- porque así maximizamos el torque, con el radio o distancia siendo máximo.
- si pusieramos la manilla al medio de la puerta, tendríamos que ejercer el doble de fuerza para lograr el mismo torque que en el extremo.
- si pusieramos la manilla en el eje de rotación, el brazo sería cero, y sin importar la fuerza, no habría torque y con eso no podríamos abrir la puerta.
- si hacemos la fuerza paralela a la distancia r, en vez de perpendicular, el ángulo entre ambos es 0 o 180 grados, y con eso sin(ángulo) es 0, y la puerta no gira en torno a su eje de rotación.

## referencias

- https://www.cliffsnotes.com/study-guides/physics/classical-mechanics/rotational-motion-of-a-rigid-body
- https://www.khanacademy.org/science/high-school-physics#torque-and-angular-momentum
