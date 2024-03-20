# MetodosNumericosT3

## Italia Yoselin Lozada Olvera

## Método de Eliminación Gaussiana
### Descripcion 

Es un método para resolver sistemas de ecuaciones lineales.
El proceso implica transformar la matriz de coeficientes del sistema en una forma triangular superior mediante operaciones elementales de fila.
Luego, se resuelven las ecuaciones resultantes a partir de la forma triangular superior, generalmente utilizando sustitución hacia atrás.

### Ejercicios en java

[Ejemplos](https://github.com/ItaliaYLO/MetodosNumericosT3/blob/main/Problemario/gaussiana.txt)


## Método de Gauss Jordan
### Descripcion 
Es un algoritmo utilizado para resolver sistemas de ecuaciones lineales mediante la eliminación de Gauss, seguida de la eliminación de Gauss-Jordan.
Consiste en transformar la matriz de coeficientes ampliada del sistema de ecuaciones en una forma escalonada reducida por filas mediante operaciones elementales de fila, tales como sumar un múltiplo de una fila a otra o intercambiar filas.
Una vez que la matriz está en forma escalonada reducida por filas, se puede leer directamente la solución del sistema de ecuaciones.

### Ejercicios en java
[Ejemplos](https://github.com/ItaliaYLO/MetodosNumericosT3/blob/main/Problemario/GaussJordan.txt)


## Método de Gauss Seidel
### Descripcion 
Es un método iterativo para resolver sistemas de ecuaciones lineales.
Este método mejora el método de Jacobi al actualizar los valores de las incógnitas a medida que se calculan, en lugar de esperar hasta que se completen todos los cálculos para una iteración.
Los nuevos valores calculados se utilizan inmediatamente en el cálculo de los siguientes valores.

### Ejercicios en java
[Ejemplos](https://github.com/ItaliaYLO/MetodosNumericosT3/blob/main/Problemario/gaussseidel.txt)


## Método de Jacobi
### Descripcion 
Es un método iterativo para resolver sistemas de ecuaciones lineales.
En cada iteración, se calcula una nueva aproximación para las incógnitas basada en las aproximaciones anteriores.
A diferencia del método de Gauss-Seidel, en el método de Jacobi, se utiliza la misma iteración para calcular todas las nuevas aproximaciones, por lo que los nuevos valores solo se utilizan en la siguiente iteración.
Aunque más simple conceptualmente que el método de Gauss-Seidel, el método de Jacobi puede ser menos eficiente en términos de velocidad de convergencia.

### Ejercicios en java
[Ejemplos](https://github.com/ItaliaYLO/MetodosNumericosT3/blob/main/Problemario/jacobi.txt)

