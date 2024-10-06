# Metodos algebraicos

-Estos métodos utilizan herramientas algebraicas para ajustar y controlar el comportamiento del sistema en lazo cerrado, logrando la respuesta deseada en el sistema.

-El principio clave de estos métodos es modificar la función de transferencia en lazo cerrado para que el sistema alcance una respuesta específica, alineada con el comportamiento deseado.

-Existen dos enfoques principales para aplicar estos métodos: uno basado en la igualación de modelo y otro en la igualación de coeficientes. Ambos enfoques buscan optimizar el rendimiento del sistema en función de parámetros específicos.

Cuando se tiene un sistema de ecuaciones (es decir 2 o más ecuaciones), se
pueden utilizar estos métodos.

Los 3 métodos algebraicos son:

- Igualación
- Sustitución
- Sumas y Restas

## 1. Igualación de modelo por métodos algebráicos

La igualación de modelo por métodos algebraicos es una técnica que consiste en modificar la función de transferencia de un sistema en lazo cerrado para que coincida con la función de transferencia de un modelo de referencia deseado. Esto se logra ajustando los parámetros del controlador para que el sistema real tenga un comportamiento similar al modelo objetivo.

se presento el sigiente ejemplo por igualacion de modelos:

![Figura de prueba](Imagenes/pri1.png)
![Figura de prueba](Imagenes/sec2.png)

## 2. Igualación de coeficientes:

Luego se nos explica la igualación de coeficientes que consta de un método algebraico utilizado en el diseño de controladores. Su objetivo es ajustar los parámetros del sistema de control (por ejemplo, ganancias de un controlador) de manera que la función de transferencia en lazo abierto del sistema tenga la forma deseada, coincidiendo los coeficientes de las expresiones polinómicas en el numerador y el denominador.

se explica uno de los ejemplos con respecto a la igualacion de coeficientes:

![Figura de prueba](Imagenes/tre3.png)

En algunos casos no se puede solucionar por acción proporcional, entonces toca usar otro método como lo son las funciones causales, en estas toca tener un par de consideraciones, entre las cuales encontramos que las funciones de planta y de controlador deben ser propias otra es que La igualación se realiza en el polinomio característico por lo tanto no hay control sobre la ubicación de los ceros del sistema.
Una vez realizado este procedimiento el polinomio debe tener el mismo numero de incógnitas como de términos. 

![Figura de prueba](Imagenes/cua4.png)




## 6. Conclusiones

- El método de igualación de coeficientes nos permite diseñar controladores ajustando con precisión los coeficientes de las funciones de transferencia, esto nos permite garantizar que el sistema siga un comportamiento dinámico que se desea.
- En igualación de coeficientes en lazo abierto se puede aplicar tanto en sistemas continuos como discretos, proporcionando una herramienta flexible para el diseño de controladores.
  









