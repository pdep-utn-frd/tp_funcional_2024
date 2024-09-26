# Trabajo Practico de Funcional

Se desea procesar un conjunto de organizaciones de diferentes industrias para poder realizar diferentes consultas sobre ellas.
De cada organizacion se conoce su nombre, su sitio web, el pais donde fue fundada, una breve descripcion, el año en el que fue fundada, la industria a la que pertenece y su cantidad de empleados actual.
El objetivo final es poder realizar el analisis sobre un archivo [CSV](https://es.wikipedia.org/wiki/Valores_separados_por_comas) (llamado `organizaciones.csv`).
Por suerte otro equipo programo un modulo llamado [Utiles](/Utiles.hs) con varias funciones utilitarias para leer archivos y parsear los campos del mismo. Por lo que solamente deberemos preocuparnos de modelar los tipos de datos y escribir las funciones necesarias para realizar el analisis.

## Tareas a realizar

1.⁠ ⁠Modelar el tipo de dato `Organizacion`. Tener en cuenta todos los campos mencionados.

2.⁠ ⁠Escribir una función `organizacionMasVieja`, que dada una lista de organizaciones devuelva la organización que primero se fundó.

3.⁠ ⁠⁠Escribir una función que dadas 2 organizaciones, devuelva la suma de los empleados de ambas.

4.⁠ ⁠⁠Utilizar la función definida en el punto anterior para escribir una función `totalDeEmpleados`, que dada una lista de organizaciones devuelva la sumatoria de todos los empleados de las organizaciones de la lista. 

5.⁠ ⁠⁠Escribir una versión alternativa, sin utilizar la función del punto 3 y utilizando composición de funciones.

6.⁠ ⁠Escribir una función que devuelva la organización del sector de plásticos ("Plastics" en en el archivo) con mayor cantidad de empleados y que haya sido fundada luego de 1960. Utilizar composición de funciones.

7.⁠ ⁠⁠Escribir una función que dada una lista de organizaciones devuelva True si alguna fue fundada en Argentina.

8.⁠ ⁠⁠Escribir una función llamada `ampliarOrganizacion` que dada una organización y un numeto, aumente la cantidad de empleados de esa organización en esa cantidad.

9.⁠ ⁠⁠Utilizando la función del punto anterior escribir una función `ampliarOrganizaciones` que dada una lista de organizaciones, aumente la cantidad de empleados de todas ellas en 10%.

10. Dada una lista de organizaciones, se desea filtrar por diferentes criterios:
    - Organizaciones cuyo nombre tiene mas de 10 caracteres.
    - Organizaciones con una cantidad par de empleados.
    - Organizaciones fundadas despues del 2000 y ademas con mas de 1000 empleados.
Definir una unica funcion que permita tomar el criterio por parametro y realice el filtrado.
Dar ejemplos de consulta utilizando tanto expresiones lambda como aplicacion parcial para los criterios.

11. Calcular el promedio de empleados de una lista de organizaciones.

12. Dada una lista de organizaciones, verificar que no hay organizaciones repetidas. Evaluar la funcion con la lista completa de organizaciones del archivo `organizaciones.csv` y verificar que ese es el caso.

13. Evaluar todas las funciones definidas en los puntos anteriores usando la lista con todas las organizaciones.
