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

$$trabajo_1 = 80 \cdot J = 80 \cdot 2.39 \cdot 10^{-4} \cdot kcal =  8 \cdot 2.39 \cdot 10^{-3} \cdot kcal \approx 8 \cdot \frac{10}{4} \cdot 10^{-3} \cdot kcal \approx 2 \cdot 10^{-2} \cdot kcal \approx 0.02 kcal$$

$$trabajo_2 = 0 \cdot J = 0 \cdot kcal$$

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

a) cuánta energía gastamos si subimos el monte Everest? si una manzana tiene 100 kcal, cuántas manzanas necesitas comer para subir el monte Everest.

b) cuál es la potencia asociada a esta energía, si subimos el monte Everest en 1 hora? y si lo subimos en 1 día?

## solución ejercicio-03

a)

primero, encontremos los datos en el enunciado o internet:

- altura del Monte Everest = 8849 metros sobre el nivel del mar.
- energía en una manzana = 100 kcal

segundo, hagamos los supuestos:

- masa de una persona promedio = 80 kilos
- energía solamente gastada en subir en línea recta con velocidad constante.

con esto, podemos decir que la fuerza de subida se contrapone a nuestro peso, para así lograr subir con velocidad constante y por lo tanto aceleración cero:

$$fuerzas = masa \cdot aceleración$$

y reemplazando:

$$subida - peso = masa \cdot 0$$

y con esto, despejamos la fuerza de subida:

$$subida = peso = masa \cdot gravedad$$

y con esto, podemos plantear el trabajo que realizamos como:

$$trabajo = fuerza \cdot desplazamiento \cdot cos(theta)$$

donde:

- fuerza = subida = masa por aceleración
- desplazamiento = altura monte Everest
- ángulo es 0, porque la fuerza y el desplazamiento son paralelos.

y reemplazando:

$$trabajo = m \cdot g \cdot altura_{Everest} \cdot cos(0)$$

y desarrollando:

$$trabajo = 80 kg \cdot 10 \frac{m}{s^2} \cdot 8849 m \cdot 1$$

y agrupando números y unidades:

$$trabajo = 800 \cdot 8849 \cdot \frac{kg \cdot m^2}{s^2}$$

y como masa por aceleración es Newton, y Newton por metro es Joule, podemos resumir las unidades como Joule, entonces:

$$trabajo = 800 \cdot 8849 \cdot J = 7079200 \cdot J$$

la energía necesaria es aproxidamante 7 millones de Joule!

y eso expresado en kilocalorías:

$$trabajo = 7,079,200 \cdot J = 7,079,200 \cdot 2.39 \cdot 10^{-4} \cdot kcal = 16,919,288 \cdot 10^{-4} \cdot kcal$$

y si aproximamos:

$$trabajo = 16,919,288 \cdot 10^{-4} \cdot kcal \approx 17 \cdot 10^{6} \cdot 10^{-4} \cdot kcal \approx 1700 kcal$$

el trabajo ejercido en subir el monte Everest es aproximadamente 1700 kcal.

y si una manzana tiene 100 kcal, entonces el número de manzanas es:

$$manzanas = \frac{trabajo}{energía_{manzana}} = \frac{1700 kcal}{\frac{100 kcal}{manzana}} = 17 manzanas$$

se necesitan el equivalente a 17 manzanas para subir el monte Everest.

este ejercicio nos muestra conversiones entre Joule y kcal, y también el resultado de condiciones ideales, por ejemplo, aquí asumimos que la escalada es hacia arriba y no hay fuerza de fricción al caminar y rodear la montaña.

b)

si la energía que calculamos es aproximadamente 7 millones de Joule, entonces la potencia de hacer esto en una unidad de tiempo es:

$$potencia(t) = \frac{trabajo}{t}$$

y si reemplazamos tiempo por 1 hora, tenemos que la potencia asociada es:

$$potencia_{t=1 hora} = \frac{7 \cdot 10^6 \cdot J}{1 hora}$$

convertimos la hora a segundos:

$$potencia_{t=1 hora} = \frac{7 \cdot 10^6 \cdot J}{60 \cdot 60 s}$$

y como 1 W = 1 J / 1 s, entonces:

$$potencia_{t=1 hora} = \frac{7 \cdot 10^4}{36} W$$

y desarollando:

$$potencia_{t=1 hora} = \frac{7 \cdot 100 \cdot 10^2}{36} W = \frac{7 \cdot 25 \cdot 10^2}{9} W$$

y entonces el resultado es:

$$potencia_{t=1 hora} = \frac{175 \cdot 10^2}{9} W \approx 1750 W$$

el resultado de la potencia en una hora es aproxidamente 1750 W.

si ahora queremos ver la potencia en un día, podemos plantearla:

$$potencia_{t=1 día} = \frac{7 \cdot 10^6 \cdot J}{1 día}$$

y si expresamos 1 día por su equivalente 24 horas:

$$potencia_{t=1 día} = \frac{7 \cdot 10^6 \cdot J}{24 horas}$$

y con esto, podemos expresar la potencia con un día como la potencia con una hora, dividida en 24:

$$potencia_{t=1 día} = \frac{7 \cdot 10^6 \cdot J}{1 hora} \cdot {1}{24}$$

y entonces:

$$potencia_{t=1 día} \approx \frac{1750 W}{24} \approx 73 W$$

entonces, con esto vemos que la misma energía de subir el monte Everest, la podemos distribuir en distintos tiempos, para obtener distintas potencias, y los resultados son muy distintos.

porque la potencia es una medida de cuánta energía se transfiere por unidad de tiempo, entonces hacer un trabajo en menos tiempo consume más potencia, que hacer el mismo trabajo en más tiempo!
