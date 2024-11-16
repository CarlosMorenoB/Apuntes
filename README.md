# Solucion del Parcial

-En la anterior clase se hizo la prueba del parcial, se da solucion al parcial de la sigiente manera:


## 1. Primer punto:
las sigientes ecuaciones se generan de forma manual con respecto a la solucion del primer punto presentado en el parcial:

$$ G(z) = \frac{1.62 \times 10^{-7} z^2 + 6.25 \times 10^{-7} z + 1.53 \times 10^{-7}}{z^3 - 2.87z^2 + 2.75z - 0.88} $$

$$ p_1 = -100 $$
$$ p_2 = -100  $$
$$ p_3 = -100$$
$$ p_4 = -2 + 2.73j $$
$$ p_5 = -2 - 2.73j $$

$$ (z + 100)(z + 100)(z + 100)(z + 2 + 2.73j)(z + 2 - 2.73j) $$

$$ (z^2 200z + 10^4)(z + 100)(z^2 + 2z - 2.73jz + 2z + 4 - 5.16j + 2.73jz + 5.46j + 7.45) $$

$$ (z^3 + 100z^2 + 200z^2 + 2\times10^4z + 10^4z + 10^6)(z^2 + 4z + 11.45) $$

$$ (z^3 + 300z^2 + 3\times10^4z + 10^6)(z^2 + 4z + 11.45) $$ 

$$ (z^5 + 4z^4 + 11.45z^3 + 300z^4 + 1.2\times10^3z^3 + 3.43\times10^3z^2 + 3\times10^4z^3 + 12\times10^4z^2 + 34.35z + 10^6z^2 + 4\times10^6z + 11.45\times10^6) $$

$$ (z^5 + 304z^4 + 31.21\times10^3z^3 + 1.12\times10^6z^2 + 4\times10^6z + 11.45\times10^6) $$


$$ G(z) = \frac{1}{z^5 + 304z^4 + 31.21\times10^3z^3 + 1.12\times10^6z^2 + 4\times10^6z + 11.45\times10^6} $$

$$ G(z) = \frac{G(0)}{G(z)(1-Go(z)} $$

$$ G(z) = \frac{ \frac{1}{z^5 + 304z^4 + 31.21\times10^3z^3 + 1.12\times10^6z^2 + 4\times10^6z + 11.45\times10^6}} { \frac{1.61\times10^-7z^2 + 6.25\times10^-7 + 1.53\times10^-7}{z^3 - 2.87z^2 + 2.75z - 0.88}(1-{ \frac{1}{z^5 + 304z^4 + 31.21\times10^3z^3 + 1.12\times10^6z^2 + 4\times10^6z + 11.45\times10^6}})} $$

$$ G(z) = \frac{z^3 - 2.87z^2 + 2.75z -0.88}{(1.61\times10^-7 z^2 + 6.25\times10^-7z + 1.53\times10^-7)(z^5 +304z^4 + 31.21\times10^3z^5 + 1.12\times10^6z^2+ 4\times10^6z + 11.45\times10^6)} $$

$$ C(z) = \frac{A0 + A1z + A2z^2}{B0 + B1z + B2z^2} $$

$$ G(o) = \frac{C(z) + G(z)}{ 1- C(z) + G(z)} $$

$$  G(o) =\frac{ (\frac{A0 + A1z + A2z^2}{B0 + B1z + B2z^2})(\frac{1.61\times10^-7z^2 + 6.25\times10^-7 + 1.53\times10^-7}{z^3 - 2.87z^2 + 2.75z -0.88})}{1-(\frac{A0 + A1z + A2z^2}{B0 + B1z + B2z^2})(\frac{1.61\times10^-7z^2 + 6.25\times10^-7 + 1.53\times10^-7}{z^3 - 2.87z^2 + 2.75z -0.88})}  $$

$$ (B0 + B1z + B2z^2)(z^3 - 2.87z^2 + 2.75z -0.88) + (A0 + A1z + A2z^2)(1.61\times10^-7z^2 + 6.25\times10^-7 + 1.53\times10^-7)  $$

$$ z^3B0 - 2.87B0^z2 + 1.75B0z - 0.88B0 + 8.z^4 - 2.87B1z^3 + 2.75B1z^2 - 0.88B1z - B2z^5 - 2.87B2z^4 + 2.75B2z^3 - 0.88B2z^2 + 1.61\times10^-7A0z^2 + 6.25\times10^-7A0z + 1.53\times10^-7A0 + 1.61\times10^-7A1z^3 + 6.25\times10^-7A1z^2 + 1.53\times10^-7A1z + 1.61\times10^-7A2z^4 + 6.25\times10^-7A2z^3 + 1.53\times10^-7A2z^2 $$

$$ 1 = B2 $$

$$ 304= B1 - 2.87B2 + 1.61\times10^-7A2 $$ 

$$ 31.21\times10^3 = B0 - 2.87B1 + 2.75B2 + 1.61\times10^-7A1 + 6.25\times10^-7A2 $$

$$ 1.12\times10^6 = -2.87B0 + 2.75B1 - 0.88B2 + 1.61\times10^-7A0 + 6.25\times10^-7A1 + 1.53\times10^-7 A2 $$

$$ 4\times10^6 = 2.75B0 - 0.88B1 + 6.25\times10^-7A0 + 1.53\times10^-7A1 $$

$$ 11.45\times10^6 = -0.88B0 + 1.53\times10^-7A0 $$



## 2. Segundo punto:

En el segundo punto había que escribir si el sistema era estable o no dependiendo de la grafica y lo previamente visto en las diapositivas mostradas.
Con respecto a lo anterior visto se da que el sistema es estable.

$$ MP > -180° $$

$$ MG > 0 $$

ESTABLE

![image alt](https://github.com/CarlosMorenoB/Apuntes/blob/fe4ca7e15518e9b6a6bcc82c76e5ec0c98c01f69/Imagenes/Segundo.png)



## 3. Tercer Punto:

El ultimo punto constaba de averiguar el punto:
  

![image alt](https://github.com/CarlosMorenoB/Apuntes/blob/fe4ca7e15518e9b6a6bcc82c76e5ec0c98c01f69/Imagenes/Segundo.png)








