# ayudantia-12

## ejercicio-01: fuerza eléctrica (30 minutos)

a) cuántos electrones equivalen a 32 Coulomb?

b) cuánta es la energía eléctrica entre un protón y un electrón, separados por 10 cm? es de atracción o repulsión?

## solución ejercicio-01

a)

sabemos que la carga de un electron es igual a

$$q_{electron} = 1.6 \cdot 10^{-19} \cdot Coulomb$$

entonces queremos encontrar el múltiplo X que logra llegar a 32 Coulomb:

$$32 \cdot Coulomb = X \cdot q_{electron}$$

y reemplazando la carga del electron

$$32 \cdot Coulomb = X \cdot  1.6 \cdot 10^{-19} \cdot Coulomb$$

podemos dividir por Coulomb y por 16 y resulta en:

$$2 = X \cdot  0.1 \cdot 10^{-19}$$

multiplicando por 10 elevado a 20:

$$2 \cdot 10^{20} = X$$

entonces la cantidad de electrones necesarios para una carga de 16 C es de 2 por 10 elevado a 20.

b)

la fuerza eléctrica está dada por

$$F_{electrica} = K \cdot \frac{q_1 \cdot q_2}{r^2}$$

la constante K de Coulomb tiene el siguiente valor y unidades:

$$K \approx 9 \cdot 10^9 \cdot \frac{N \cdot m^2}{C^2}$$

la carga es igual entre un protón y un electrón, solamente tienen signos distintos, y tiene valor:

$$1 \cdot electron \approx 1.6 \cdot 10^{-19} \cdot C$$

entonces reemplazando los valores:

$$F_{electrica} = (9 \cdot 10^9 \cdot \frac{N \cdot m^2}{C^2}) \cdot \frac{( 1.6 \cdot 10^{-19}  \cdot C) \cdot ( -1.6 \cdot 10^{-19} \cdot  C)}{(\frac{10}{100} \cdot m)^2}$$

y ordenando números, potencias de 10 y unidades:

$$F_{electrica} = -(9 \cdot 1.6^{2} \cdot 100) \cdot  (10^9 \cdot 10^{-38}) \cdot N$$

y simplificando:

$$F_{electrica} = -(9 \cdot 1.6^{2})\cdot 10^{-27} \cdot N$$

ese es el valor de la fuerza eléctrica, y como es un electrón y un protón con cargas de signo distinto, es una fuerza de atracción.

## ejercicio-02: energía y potencia domiciliaria (30 minutos)

a) si el voltaje domiciliario en Chile es de 220 V, y la corriente máxima es de 10 A, cuánta es la potencia máxima que puede brindar un enchufe?

b) si un refrigerador consume una potencia de 250 W, cuánta corriente le pide al enchufe? cuánto gasta ese refrigerador en un mes?

dato:

$$1 \cdot kWh = 100 \cdot CLP$$

## solución ejercicio-02

a)

la relación entre potencia, voltaje y corriente está dada por:

$$potencia = voltaje \cdot corriente$$

entonces, reemplazando con voltaje máximo y corriente máxima, tenemos una potencia máxima:

$$P_{max} = 220 \cdot V \cdot 10 \cdot A = 2,200 \cdot W = 2.2 \cdot kW$$

la potencia máxima es 2.2 kW.

b)

partimos con la relación entre potencia, voltaje y corriente

$$potencia = voltaje \cdot corriente$$

podemos despejar la corriente

$$corriente = \frac{potencia}{voltaje}$$

y reemplazando los valores

$$corriente = \frac{250 \cdot W}{220 V} = \frac{25}{22} \cdot A \approx 1.13 \cdot A$$

la corriente que le pide el refrigerador al enchufe es de 1.13 A. veamos ahora el costo de tener este refrigerador enchufado por un mes.

en una hora, este refrigerador consume 250 Wh.

en un día, es 24 veces esto, y en un mes promedio, 30 veces esto, calculemos esta energía en un mes:

$$energía_{mes} = 30 \cdot 24 \cdot 250 \cdot Wh$$

y esto en kWh, es igual a

$$energía_{mes} = 180 \cdot kWh$$

si un kWh vale 100 pesos chilenos, entonces el precio de 180 veces esto es igual a:

$$precio_{mes} = 180 \cdot 100 CLP = 18,000 CLP$$

el costo de tener este refrigerador enchufado y funcionando a máxima potencia todo el mes es de 18 mil pesos chilenos. el costo real es menor, ya que el refrigerador no siempre está funcionando a su máxima potencia!

## ejercicio-03: energía en una batería (30 minutos)

a) si tenemos una batería de voltaje 1.5V y capacidad de 1,200 mAh, cuánta carga tiene en Coulombs?

b) si la batería la usamos para alimentar un circuito con una potencia de 50 mW, cuánta corriente extrae de la batería? y cuánto se demora la batería en descargarse?

## solución ejercicio-03

a)

convirtamos la capacidad de la batería a Joules:

$$capacidad = 1,200 mAh = 1.2 \cdot A \cdot hora$$

sabemos que Ampère es carga por segundo, entonces:

$$capacidad = 1.2 \cdot \frac{C}{s} \cdot hora$$

y una hora es 60 \* 60 segundos, entonces

$$capacidad = 1.2 \cdot \frac{C}{s} \cdot 60 \cdot 60 \cdot s$$

y simplificando

$$capacidad = 12 \cdot 360 \cdot C = 4320 C$$

b)

la batería entrega 1.5 V a cierta corriente X, para alimentar un circuito que necesita 50 mW de potencia, y sabemos que la relación entre voltaje, corriente y potencia es:

$$P = V \cdot I$$

y despejando la corriente I

$$I = \frac{P}{V}$$

y reemplazando los valores

$$I = \frac{50 \cdot mW}{1.5 V}$$

y desarollando

$$I = \frac{50 \cdot V \cdot A}{1000 \cdot 1.5 V}$$

$$I = \frac{50 \cdot A}{1500}$$

$$I = \frac{5 \cdot A}{150}$$

$$I = \frac{1}{30} \cdot A$$

con esta corriente, podemos tomar su capacidad en mAh, que significa la corriente que es capaz de entregar por hora, y plantear la ecuación.

$$capacidad = corriente \cdot tiempo$$

en esta ecuación, la capacidad es constante, y la corriente y el tiempo tienen proporcionalidad inversa. reemplacemos con la corriente que acabamos de calcular, para encontrar el tiempo correspondiente.

$$1,200 mAh = \frac{1}{30} \cdot A \cdot tiempo$$

dividimos por A y expandimos milis en 1/1000:

$$\frac{1200}{1000} \cdot h = \frac{1}{30} \cdot tiempo$$

multiplicamos por 30 a ambos lados para despejar tiempo:

$$tiempo = \frac{1200 \cdot 30}{1000} \cdot h$$

y simplificando

$$tiempo = 12 \cdot 3 \cdot h = 36 \cdot horas$$

con esto, hemos llegado al resultado de que esta pila con capacidad de 1200 mAh, cuando alimenta un circuito de 50 mW de potencia, lo puede hacer durante 36 horas.
