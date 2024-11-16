# Solucion del Parcial

-En la anterior clase se hizo la prueba del parcial, se da solucion al parcial de la sigiente manera:


## 1. Primer punto:
las sigientes ecuaciones se generan de forma manual con respecto a la solucion del primer punto del grupo:

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

$$ G(z) = \frac{ \frac{1}{z^5 + 304z^4 + 31.21\times10^3z^3 + 1.12\times10^6z^2 + 4\times10^6z + 11.45\times10^6}} { \frac{1.61x10^-7z^2 + 6.25x10^-7 + 1.53x10^-7}{z^5 - 2.87z^2 + 2.75z - 0.88}(1-{ \frac{1}{z^5 + 304z^4 + 31.21\times10^3z^3 + 1.12\times10^6z^2 + 4\times10^6z + 11.45\times10^6}})} $$


## 2. Segundo punto:




## 6. Conclusiones

- El método de igualación de coeficientes nos permite diseñar controladores ajustando con precisión los coeficientes de las funciones de transferencia, esto nos permite garantizar que el sistema siga un comportamiento dinámico que se desea.
- En igualación de coeficientes en lazo abierto se puede aplicar tanto en sistemas continuos como discretos, proporcionando una herramienta flexible para el diseño de controladores.
  









