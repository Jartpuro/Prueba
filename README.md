# U2_Informe_01

Estimación del valor de π

La siguiente figura sugiere como estimar el valor de π con una simulación. En la figura, un circuito con un área igual a π/4, está inscrito en un cuadrado cuya área es igual a 1. Se elige de forma aleatoria n puntos dentro del cuadrado . La probabilidad de que un punto esté dentro del círculo es igual a la fracción del área del cuadrado que abarca a este, la cual es π/4. Por tanto, se puede estimar el valor de π/4 al contar el número de puntos dentro del círculo, para obtener la estimación de π/4. De este último resultado se encontrar una aproximación para el valor de π.


Pasos sugeridos:
a. Genere n  coordenadas x: X1,...,Xn. Utilice la distribución uniforme con valor mínimo de 0 y valor máximo de 1. La distribución uniforme genera variables aleatorias que tienen la misma probabilidad de venir de cualquier parte del intervalo (0,1).
b. Genere 1000 coordenadas y : Y1,...,Yn, utilizando nuevamente la distribución uniforme con valor mínimo de 0 y valor máximo de 1.
c. Cada punto (Xi,Yi) se encuentra dentro del círculo si su distancia desde el centro (0.5,0.5) es menor a 0.5. Para cada par (Xi,Yi) determine si la distancia desde el centro es menor a 0.5. Esto último se puede realizar al calcular el valor (Xi−0.5)^2+(Yi−0.5)^2, que es el cuadrado de la distancia, y al determinar si es menor que 0.25.
d. ¿Cuántos de los puntos están dentro del círculo? ¿Cuál es su estimación de π?
e. Con sólo 1000 puntos, es probable que la estimación presente un error de 0.05 o más. Genere una simulación con 10000 y 100000 puntos validando si tiene mayores probabilidades de dar como resultado una estimación muy cercana al valor verdadero.
f. funciones recomendadas : runif(), function(){}

