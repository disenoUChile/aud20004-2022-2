# ayudantia-05

unidad 3: energía y cantidad de movimiento

## ejercicio-01 (30 minutos)

a) si un cuerpo de masa 20 kg se encuentra a una altura de 20 metros de la superficie de la tierra, con una velocidad 0, cuál es su energía total?

b) si el cuerpo cae en caída libre, cuál es la velocidad del cuerpo cuando llega al suelo?

## solución ejercicio-01

a)

tenemos que la ecuación de la energía total de un cuerpo es:

$$E_{h=20m} = E_p + E_c = m \cdot g \cdot h + \frac{1}{2} \cdot m \cdot v^2$$

si tomamos la tierra como la referencia para la altura y reemplazamos con velocidad igual a cero:

$$E_{h=20m} = m \cdot g \cdot h  + \frac{1}{2} \cdot m \cdot 0^2 = m \cdot g \cdot h $$

y reemplazando con los valores de masa y gravedad, tenemos:

$$E_{h=20m} = 20 kg \cdot 10 \frac{m}{s^2} \cdot 20 m$$

y multiplicando números y unidades:

$$E_{h=20m} = 4000 \cdot \frac{kg \cdot m^2}{s^2}$$

y como masa por aceleración es fuerza, y fuerza por distancia es J:

$$E_{h=20m} = 4000 J$$

b)

en el suelo, tenemos que la altura es 0, y la ecuación de la energía queda:

$$E_{h=0m} = E_p + E_c = m \cdot g \cdot 0 + \frac{1}{2} \cdot m \cdot v^2 = \frac{1}{2} \cdot m \cdot v^2$$

por conservación de la energía, la energía en ambas alturas es igual:

$$E_{h=20m} = E_{h=0m}$$

y reemplazando:

$$4000 J = \frac{1}{2} \cdot m \cdot v^2$$

y desarollando:

$$4000 J = \frac{1}{2} \cdot 20 kg \cdot v^2$$

y simplificando:

$$4000 J = 10 kg \cdot v^2$$

y diviendo por 10 kg a ambos lados:

$$v^2 = 400 J$$

$$400 \frac{J}{kg} = v^2$$

como Joule es Newton por metro:

$$v^2 = 400 \frac{N \cdot m}{kg}$$

como Newton es kg multiplicado por metros y dividido en segundos cuadrados ( F = m \* a):

$$v^2 = 400 \frac{kg \cdot m^2}{kg \cdot s^2}$$

y simplificando:

$$v^2 = 400 \frac{m^2}{s^2}$$

y aplicando raíz cuadrada a ambos lados:

$$v = 20 \frac{m}{s}$$

con lo que la respuesta es que al tocar el suelo, la velocidad del cuerpo es de 20 metros / segundo.

## ejercicio-02 (30 minutos)

a) si levantamos una masa de 4 kg desde el suelo y la levantamos 2 metros, cuánto trabajo hacemos? y si caminamos 20 metros en línea recta, cuánto trabajo hacemos? expresar resultados en Joule y en kilocalorías, sabiendo que:

$$1 J = 2.39 \cdot 10^{-4} kcal$$

b) quién hace el trabajo sobre quién? identificar el rol del cuerpo de masa m, la tierra, y nosotros.

## solución ejercicio-02

a)

si suponemos que la fuerza de levante que ejercemos sobre el cuerpo es constante, de igual magnitud al peso del cuerpo y en dirección contraria, tenemos según la segunda ley de Newton:

$$levante - peso = 0 = m \cdot a$$

con lo que el cuerpo no acelera, su velocidad es constante, y podemos escribir nuestra fuerza de levante como:

$$levante = peso = m \cdot g$$

sabemos que la ecuación de trabajo para este caso es:

$$trabajo_1 = fuerza \cdot desplazamiento \cdot cos(\theta)$$

y reemplazando la fuerza encontrada, tenemos:

$$trabajo_1 = m \cdot g \cdot desplazamiento \cdot cos(\theta)$$

sabemos los datos:

- masa del cuerpo = 4 kg
- gravedad = 10 metros / segundos cuadrados
- desplazamiento = 2 metros
- ángulo = 0 grados

reemplazamos:

$$trabajo_1 = 4 kg \cdot 10 \frac{m}{s^2} \cdot 2 m \cdot cos(0)$$

agrupamos números y unidades

$$trabajo_1 = 80 \cdot \frac{kg \cdot m^2}{s^2}$$

y simplificamos las unidades:

$$trabajo_1 = 80 \cdot N \cdot m = 80 J$$

veamos ahora el siguiente caso, de qué ocurre si caminamos con el objeto en línea recta.

$$trabajo_2 = fuerza \cdot desplazamiento \cdot cos(\theta)$$

la fuerza que ejercemos sobre el cuerpo para mantenerlo a una altura constante y poder caminar con el cuerpo, es igual en magnitud al peso, y en dirección perpendicular a la tierra.

el desplazamiento que estamos haciendo es paralelo a la tierra, por lo que el ángulo entre la fuerza y el desplazamiento es 90 grados.

el coseno de 90 grados es 0, por lo que la ecuación queda:

$$trabajo_2 = m \cdot g \cdot desplazamiento \cdot 0$$

vemos que sin importar la gravedad ni la masa, como el desplazamiento y la fuerza ejercida sobre el objeto son perpendiculares, el trabajo es 0.

el cuerpo no ve trabajo ni cambios de energía en él mismo, su energía no cambia, pero la energía de nosotros sí. de hecho, dependiendo del peso del cuerpo que acarreamos al caminar eso afecta nuestros músculos y nosotros sí hacemos trabajo, pero al caminar y en el sistema nosotros-tierra.

convirtamos ahora estos trabajos encontrados a kilocalorías:

$$trabajo_1 = 4000 \cdot J = 4000 \cdot 2.39 \cdot 10^{-4} \cdot kcal = 9.56 \cdot 10^{-1} \cdot kcal \approx 1 \cdot kcal$$

$$trabajo_1 = 0 \cdot J = 0 \cdot kcal$$

b)

en el primer caso, cuando estamos levantando el cuerpo, estos son los roles con respecto a las fuerzas:

- la tierra ejerce la fuerza de peso sobre el objeto y nosotros
- nosotros ejercemos una fuerza de levante, contraria al peso
- el cuerpo recibe la aplicación de ambas fuerzas que se anulan y su velocidad es constante.

y con respecto a los trabajos y energías:

- nosotros ejercemos un trabajo, y perdemos energía
- el cuerpo recibe un trabajo y gana energía, ya que su altura aumenta, y con esto su energía potencial.
- la tierra no ve un cambio en energía, ya que no hace ni recibe trabajo.

veamos ahora el segundo caso, cuando estamos caminando con el cuerpo, estos son los roles con respecto a las fuerzas:

- la tierra ejerce una fuerza de peso sobre nosotros y el cuerpo, y también fuerzas de contacto como roce, al caminar.
- nosotros ejercemos una fuerza de levante, contraria al peso
- el cuerpo recibe la aplicación de ambas fuerzas que se anulan y su velocidad es constante.

y con respecto a los trabajos y energías:

- la fuerza ejercida sobre el cuerpo es perpendicula a su desplazamiento, por lo que el trabajo sobre el cuerpo es 0 y no cambia su energía.
- nosotros al caminar ejercemos una fuerza sobre la tierra que es paralela a nuestro desplazamiento, por lo tanto hacemos trabajo sobre la tierra y perdemos energía al caminar.
- la tierra recibe el trabajo ejercido sobre ella, y gana energía.

## ejercicio-03 (30 minutos)

a)

b)

## solución ejercicio-03

a)

b)
