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

$$T_2 = 30 C = 30 + 273 K = 303 K$$

y por el enunciado nos dice que la nueva temperatura es:

$$T_3 = 100 C = 100 + 273 K = 373 K$$

encontremos el nuevo volumen según esta igualdad:

$$\frac{V_2}{T_2} = \frac{V_3}{T_3}$$

despejamos V_3:

$$V_3 = V_2 \cdot \frac{T_3}{T_2}$$

reemplazamos los valores:

$$V_3 = 10^{-1} \cdot m^3 \cdot \frac{373 K}{303 K}$$

$$V_3 = 1.23 \cdot 10^{-1} \cdot m^3$$

en este caso tenemos que la presión se mantiene constante, y como la temperatura sube, el volumen también sube.

## ejercicio-02: transferencia de calor (30 minutos)

a) cuánta energía necesitamos para subir la temperatura de un litro de agua de 0 Celsius a 100 Celsius?

datos:

$$c_{agua} = 4182 \frac{J}{kg \cdot K}$$

$$\rho_{agua} = 1 \cdot \frac{g}{cm^3}$$

b) si tenemos una masa de agua de 10 kg a temperatura 50 grados Celsius, y sumergimos una masa de oro de 5kg a temperatura 3000 grados Celsius, cuál es la temperatura final de equilibrio?

datos:

$$c_{agua} = 4182 \frac{J}{kg \cdot K}$$

$$c_{oro} = 129 \frac{J}{kg \cdot K}$$

## solución ejercicio-02

a)

para encontrar la energía, usaremos la ecuación de transferencia de calor:

$$Q = m \cdot c \cdot \Delta T$$

tenemos un volumen de agua de 1 litro, pero necesitamos la masa correspondiente, tenemos la densidad del agua, así que calculemos:

$$m_{agua} = \rho{agua} \cdot volumen_{agua}$$

y reemplazando los valores:

$$m_{agua} = 1 \cdot \frac{g}{cm^3} \cdot 1 \cdot litro$$

$$m_{agua} = 1 \cdot \frac{g}{cm^3} \cdot 1 \cdot dm^3$$

$$m_{agua} = 1 \cdot \frac{g}{cm^3} \cdot 1 \cdot (10 \cdot cm)^3$$

$$m_{agua} = 1 \cdot \frac{g}{cm^3} \cdot 1 \cdot 10^3 cm^3$$

$$m_{agua} = 1 \cdot g \cdot 10^3$$

$$m_{agua} = 1 \cdot kg$$

ahora podemos reemplazar en la ecuación de calor:

$$Q = m \cdot c \cdot \Delta T$$

podemos usar los valores en Celsius sin convertir a Kelvin, porque lo que importa es la diferencia de temperatura, y los grados Celsius y Kelvin miden lo mismo, no así los Fahrenheit!

$$Q = 1 kg \cdot  4182 \frac{J}{kg \cdot K} \cdot (100 - 0) K$$

simplificando

$$Q = 1 \cdot  4182 J \cdot 100$$

$$Q = 418200 J$$

b)

tenemos que para todo cuerpo, podemos usar la ecuación de calor

$$Q = m \cdot c \cdot \Delta T$$

si llamamos T_f a la temperatura final de equilibrio, podemos decir

planteamos la ecuación para agua

$$Q_{agua} = m_{agua} \cdot c_{agua} \cdot \Delta T_{agua}$$

reemplazamos los valores

$$Q_{agua} = 10 \cdot kg \cdot 4182 \frac{J}{kg \cdot K} \cdot (T_f - 323) K$$

y simplificamos

$$Q_{agua} = 41820 \cdot J \cdot (T_f - 323)$$

planteamos ahora la ecuación para oro:

$$Q_{oro} = m_{oro} \cdot c_{oro} \cdot \Delta T_{oro}$$

reemplazamos los valores

$$Q_{oro} = 5 kg \cdot 129 \frac{J}{kg \cdot K} \cdot (T_f - 3273) K$$

y simplificamos

$$Q_{oro} = 645 \cdot J \cdot (T_f - 3273)$$

asumimos que este es un sistema aislado, y que como la energía se conserva, la transferencia de calor será de un cuerpo a otro y podemos plantear:

$$Q_{agua} + Q_{oro} = 0$$

y reemplazando

$$41820 \cdot J \cdot (T_f - 323) + 645 \cdot J \cdot (T_f - 3273) = 0$$

y simplificando y desarrollando

$$41820 \cdot (T_f - 323) + 645 \cdot \Delta (T_f - 3273) = 0$$

$$41820 \cdot T_f - 41820 \cdot 323 + 645 \cdot T_f - 645 \cdot 3273 = 0$$

agrupamos la temperatura final a un lado de la ecuación:

$$41820 \cdot T_f + 645 \cdot T_f = 41820 \cdot 323  + 645 \cdot 3273$$

$$T_f \cdot (41820 + 645) = 41820 \cdot 323 + 645 \cdot 3273$$

y podemos despejar Tf:

$$T_f = \frac{41820 \cdot 323 + 645 \cdot 3273}{41820 + 645}$$

y calcular:

$$T_f = 367.8$$

también podemos calcular de forma aproximada

$$T_f = \frac{41820 \cdot 323 + 645 \cdot 3273}{41820 + 645}$$

$$T_f \approx \frac{41820 \cdot 323}{41820 + 645} + \frac{645 \cdot 3273}{41820 + 645}$$

$$T_f \approx 323 + 645 \cdot 0.1 \approx 323 + 64.5 \approx 387.5$$

así calculamos la temperatura en Kelvin, y para convertir a Celsius:

$$T_f = 367.8 K = (367.8 - 273) C = 94.8 C$$

o con el valor aproximado

$$T_f = 387.5 K = (387.5 - 273) C = 114.5 C$$

como comentario, el agua puede llegar máximo a 100 C, antes de evaporarse, y luego la energía se usa para pasar de estado líquido a sólido.

## ejercicio-03: expansión térmica (30 min)

a)

si tenemos una barra de cobre de largo 7 metros, a 20 grados Celsius, encontrar el largo cuando la temperatura sube a 100 grados Celsius.

dato:

$$\alpha_{cobre} = 16 \cdot 10^{-6} \frac{1}{K}$$

b)

si tenemos un cubo de cierto material desconocido, y observamos que a 50 grados Celsius su volumen es de 12 litros, y si lo enfríamos a 10 grados Celsius su volumen es de 11.85 litros, calcular su coeficiente de expansión lineal.

## solución ejercicio-03

a)

usamos la ecuación de expansión lineal:

$$\Delta L = L_0 \cdot \alpha \Delta T$$

y reemplazando los valores:

$$\Delta L = 7 m \cdot 16 \cdot 10^{-6} \frac{1}{K} (100 - 20) K$$

y despejando:

$$\Delta L = 7 m \cdot 16 \cdot 10^{-6} \cdot 80$$

$$\Delta L = 8960 \cdot 10^{-6} m = 0.896 \cdot 10^{-2} m = 0.896 cm$$

entonces la barra cambia su largo en 0.896 cm, y su largo final es 7m + 0.896 cm.

b)

sabemos que la ecuación de expansión para volúmenes es:

$$\Delta V = V_0 \cdot (3 \cdot \alpha) \cdot \Delta T$$

primero calculemos la diferencia de volumen

$$\Delta V = V_f - V_i = 11.85 litros - 12 litros = -0.15 litros$$

y si lo expresmoas en metros cúbicos

$$\Delta V = -0.15 litros = -0.15 dm^3 = -0.15 (\frac{1}{10} \cdot m)^3 = -0.15 \cdot 10^{-3} \cdot m^3$$

calculemos ahora la diferencia de temperatura correspondiente:

$$\Delta T = T_f - T_i = 10 C - 50 C = - 40 C$$

y en Kelvin, la diferencia es la misma, porque la diferencia en Celsius y Kelvin mide lo mismo:

$$\Delta T = - 40 K$$

ahora volvamos a la fòrmula de diferencia de volumen:

$$\Delta V = V_0 \cdot (3 \cdot \alpha) \cdot \Delta T$$

y despejemos el coeficiente de expansión lineal:

$$\alpha = \frac{\Delta V}{3 \cdot V_0 \cdot \Delta T}$$

y reemplazamos con los valores:

$$\alpha = \frac{-0.15 \cdot 10^{-3} \cdot m^3}{3 \cdot 12 \cdot 10^{-3} \cdot m^3 \cdot (-40 K)}$$

y despejando:

$$\alpha = \frac{-0.15}{3 \cdot 12 \cdot (-40 K)}$$

$$\alpha = \frac{0.15}{36 \cdot (40 K)}$$

$$\alpha = \frac{0.15}{1440 K} \approx 0.104 \cdot 10^{-3} \frac{1}{K}$$

entonces el coeficiente de expansión lineal es de 0.104 milis / Kelvin.

## ejercicio extra

demostrar que la temperatura mínima posible es -273 Celsius.

solución:

usando la ecuación de gases ideales:

$$P \cdot V = n \cdot R \cdot T$$

si partimos de 1 mol de gas ideal en condiciones normales:

$$n = 1 mol$$

$$P = 100 kPa$$

$$V  = 22.41 litros$$

$$T = 0 C$$

si mantenemos el volumen constante, y bajamos la presión al mínimo de 0 Pa, llegaremos a un estado de mínima energía, y podemos encontrar la temperatura ahí.

si vemos la diferencia de presión a volumen constante, podemos plantear la ecuación:

$$\Delta P = \frac{n \cdot R}{V} \cdot \Delta T$$

donde n, R y V son constantes conocidas, y como estamos yendo de 100 kPa a 0 Pa, podemos calcular Delta P:

$$\Delta P = 0 Pa - 100 kPa = -100 kPa$$

como sabemos Delta P, podemos partir de la ecuación original y despejar Delta T:

$$\Delta P = \frac{n \cdot R}{V} \cdot \Delta T$$

$$\Delta T = \frac{\Delta P \cdot V}{n \cdot R}$$

y reemplazando los valores:

$$\Delta T = \frac{-100 kPa \cdot 22.41 litros}{1 mol \cdot 8.31 \frac{J}{mol \cdot C}}$$

y despejando:

$$\Delta T = \frac{-100 \cdot kPa \cdot 22.41 \cdot 10^{-3} \cdot m^3}{8.31 \frac{J}{C}}$$

$$\Delta T = \frac{-100 \cdot Pa \cdot 22.41 \cdot m^3}{8.31 \frac{J}{C}}$$

$$\Delta T = \frac{-100 \cdot \frac{N}{m^2} \cdot 22.41 \cdot m^3}{8.31 \frac{J}{C}}$$

$$\Delta T = \frac{-100 \cdot N \cdot 22.41\cdot m}{8.31 \frac{J}{C}}$$

$$\Delta T = \frac{-100 \cdot 22.41 }{8.31} \cdot C$$

$$\Delta T \approx -269.67 \cdot C$$

entonces vemos que si la temperatura baja a 0 Pa, la diferencia de temperatura es -269.67 C, y como la temperatura inicial era 0 C, tenemos:

$$-269.67 C = T_f - T_i = T_f - 0 = T_f$$

entonces este es el mínimo de temperatura, que se aproxima mucho al resultado ideal, que es -273.15 C.
