# ayudantia-04

## ejercicio-01 (30 minutos)

a) nombrar todas las fuerzas que afectan a un cuerpo de masa m, en un plano inclinado, con aceleración cero, en el planeta tierra y dibujar el diagrama del cuerpo libre.

b) nombrar cuáles son los causantes de las fuerzas sobre la masa m.

## solución ejercicio-01

a) un cuerpo en un plano inclinado presenta 3 fuerzas:

- fuerza de peso, y en dirección hacia abajo.
- fuerza normal, en dirección perpendicular al plano inclinado.
- fuerza de roce estático, paralela al plano inclinado, que se opone al deslizamiento o movimiento del cuerpo.

![diagrama de cuerpo libre](./Friction_relative_to_normal_force_fondo_blanco.png)

b)

- la fuerza de peso existe porque nuestro cuerpo de masa m está sobre el planeta tierra, y la tierra ejerce una fuerza gravitacional sobre este cuerpo.
- la fuerza normal existe porque nuestro cuerpo de masa m está en contacto con una superficie, y por la tercera ley de Newton: como el cuerpo de masa m empuja a la superficie, la respuesta del plano es empujar al cuerpo de masa m, en la misma magnitud y en sentido contrario.
- la fuerza de roce estático existe porque nuestro cuerpo de masa m está en contacto con una superficie inclinada y en reposo. esta fuerza se opone al movimiento del cuerpo.

## ejercicio-02 (30 minutos)

a) dibujar el diagrama de cuerpo libre de un cuerpo de masa m, que está sostenido por una cuerda ideal desde el techo. la cuerda no está perpendicular al techo, sino que está en un ángulo theta.

b) aplicar la segunda ley de Newton y demostrar con ecuaciones que en esa posición, el cuerpo de masa m tiene una aceleración distinta de cero. demostrar que si la cuerda estuviera perpendicular, el cuerpo no estaría acelerando en el eje X.

## solución ejercicio-02

a)

![solución ejercicio 2a](./ej02a.jpg)

b)

como tenemos la fuerza de tensión T en una diagonal, la descomponemos según el ángulo theta, usando primero la función seno y luego coseno:

$$sin(\theta) = \frac{cateto opuesto}{hipotenusa} = \frac{T_x}{T}$$

y despejamos de esta ecuación T en eje X:

$$T_x = T \cdot sin(\theta)$$

ahora con coseno, planteamos:

$$cos(\theta) = \frac{cateto adyacente}{hipotenusa} = \frac{T_y}{T}$$

y despejamos de esta ecuación T en eje Y:

$$T_y = T \cdot cos(\theta)$$

entonces ahora sabemos que el vector de tensión T es:

$$T = T_x \cdot \hat{x} + T_y \cdot\hat{y} = T \cdot sin(\theta) \cdot \hat{x} + T \cdot cos(\theta) \cdot \hat{y}$$

y ahora sí podemos usar la segunda ley de Newton:

$$\vec{F} = m \cdot \vec{a}$$

donde descomponemos en ejes X e Y:

$$ F_x = m \cdot a_x$$

$$ F_y = m \cdot a_y$$

y luego reemplazamos para cada eje:

$$ T \cdot sin(theta) = m \cdot a_x$$

$$ T \cdot cos(theta) - W = m \cdot a_y$$

vemos que el cuerpo tiene aceleración en ambos ejes X e Y, ya que el ángulo es distinto de cero.

si la cuerda estuviera perpendicular, el ángulo sería 0, y entonces en ese caso, las ecuaciones resultarían:

$$ T \cdot 0 = m \cdot a_x$$

$$ T \cdot 1 - W = m \cdot a_y$$

y vemos que en el eje X el lado izquierdo es 0, por lo tanto la aceleración en el eje X es cero.

## ejercicio-03 (30 minutos)

con la siguiente máquina de Atwood:

![máquina de Atwood](./Atwood.png)

a) hacer supuestos de coordenadas y encontrar la aceleración en función de la gravedad y las masas, para demostrar que las distancias no afectan a la aceleración.

## solución ejercicio-03

a)

en una máquina de Atwood, tenemos que la aceleración de las masas m1 y m2 conectadas por una cuerda ideal son de igual magnitud, y dirección contraria. si asumimos que a es positiva hacia arriba, y que m1 acelera hacia arriba, y que m2 acelera hacia abajo, tenemos esta ecuación:

$$a = g \cdot \frac{m1 - m2}{m1+ m2}$$

nos damos cuenta que la aceleración es el múltiplo de 3 factores: g que es un valor positivo, la suma de las masas que también es positivo, y la resta entre m1 y m2, que definirá el signo de la aceleración así:

- si m1 > m2, entonces m1 - m2 > 0, y por lo tanto, a también es positivo, lo que tiene
