# Intervalos de Confianza para Medias y Proporciones {#cap:intervalos-confianza-1-poblacion}

## Ejercicios resueltos

1.  Se analiza la concentración de principio activo en una muestra de 10
    envases tomados de un lote de un fármaco, obteniendo los siguientes
    resultados en mg/mm$^{3}$:
    $$17.6-19.2-21.3-15.1-17.6-18.9-16.2-18.3-19.0-16.4$$

    Se pide:

    1.  Crear un conjunto de datos con la variable .

    2.  Calcular el intervalo de confianza para la media de la
        concentración del lote con nivel de confianza del 95% (nivel de
        significación $\alpha =0.05$).

        ::: indicacion
        1.  Seleccionar el menú .

        2.  En el cuadro de diálogo que aparece seleccionar la variable
            en el campo y hacer clic sobre el botón .
        :::

    3.  Calcular los intervalos de confianza para la media con niveles
        del 90% y del 99% (niveles de significación $\alpha=0.1$ y
        $\alpha=0.01$).

        ::: indicacion
        Repetir los mismos pasos del apartado anterior, cambiando el
        nivel de confianza para cada intervalo en la solapa
        :::

    4.  Si definimos la precisión del intervalo como la inversa de su
        amplitud, ¿cómo afecta a la precisión del intervalo de confianza
        el tomar niveles de significación cada vez más altos? ¿Cuál
        puede ser la explicación?

    5.  ¿Qué tamaño muestral sería necesario para obtener una estimación
        del contenido medio de principio activo con un margen de error
        de $\pm 0.5$ mg/mm$^3$ y una confianza del 95%?

        ::: indicacion
        1.  Seleccionar el menú .

        2.  En el cuadro de diálogo que aparece seleccionar la variable
            en el campo .

        3.  En la solapa marcar el estadístico y hacer clic en el botón
            .

        4.  Seleccionar el menú .

        5.  En el cuadro de diálogo que aparece introducir la
            cuasidesviación típica muestral en el campo , el nivel de
            significación deseado, en este caso $0.05$, en el campo , el
            margen de error deseado, en este caso $0.5$, en el campo , y
            hacer clic en el botón .
        :::

    6.  Si, para que sea efectivo, el fármaco debe tener una
        concentración mínima de 16 mg/mm$^3$ de principio activo, ¿se
        puede aceptar el lote como bueno? Justificar la respuesta.

2.  Una central de productos lácteos recibe diariamente la leche de dos
    granjas $X$ e $Y$. Para analizar la calidad de la leche, durante una
    temporada, se controla el contenido de materia grasa de la leche que
    proviene de ambas granjas, con los siguientes resultados:
    $$\begin{array}{ll|ll}
    \multicolumn{2}{c|}{X} & \multicolumn{2}{c}{Y} \\
    \hline
    0.34 & 0.34 & 0.28 & 0.29 \\
    0.32 & 0.35 & 0.30 & 0.32 \\
    0.33 & 0.33 & 0.32 & 0.31 \\
    0.32 & 0.32 & 0.29 & 0.29 \\
    0.33 & 0.30 & 0.31 & 0.32 \\
    0.31 & 0.32 & 0.29 & 0.31 \\
     &  & 0.33 & 0.32 \\
     &  & 0.32 & 0.33 \\
    \end{array}$$

    1.  Crear un conjunto de datos con las variables y .

    2.  Calcular el intervalo de confianza con un 95% de confianza para
        el contenido medio de materia grasa de la leche sin tener en
        cuenta si la misma procede de una u otra granja.

        ::: indicacion
        1.  Seleccionar el menú .

        2.  En el cuadro de diálogo que aparece seleccionar la variable
            en el campo y hacer clic sobre el botón .
        :::

    3.  Calcular los intervalos de confianza con un 95% de confianza
        para el contenido medio de materia grasa de la leche dividiendo
        los datos según la granja de procedencia de la leche.

        ::: indicacion
        1.  Seleccionar el menú .

        2.  En el cuadro de diálogo que aparece seleccionar la variable
            en el campo .

        3.  Seleccionar la casilla de e introducir la condición hacer
            clic sobre el botón .

        4.  Repetir los mismos pasos para el intervalo de confianza de
            la granja $Y$, introduciendo la condición en el campo .
        :::

    4.  A la vista de los intervalos obtenidos en el punto anterior, ¿se
        puede concluir que existen diferencias significativas en el
        contenido medio de grasa según la procedencia de la leche?
        Justificar la respuesta.

3.  En una encuesta realizada en una facultad, sobre si el alumnado
    utiliza habitualmente (al menos una vez a la semana) la biblioteca
    de la misma, se han obtenido los siguientes resultados:

    ::: flushleft
      Alumno      1    2    3    4    5    6    7    8    9    10   11   12   13   14   15   16   17
      ----------- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ----
      Respuesta   no   si   no   no   no   si   no   si   si   si   si   no   si   no   si   no   no

      Alumno      18   19   20   21   22   23   24   25   26   27   28   29   30   31   32   33   34
      ----------- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ----
      Respuesta   no   si   si   si   no   no   si   no   no   si   si   no   no   si   no   si   no
    :::

    1.  Crear un conjunto de datos con la variable .

    2.  Calcular el intervalo de confianza con $\alpha=0.01$ para la
        proporción del alumnado que utiliza habitualmente la biblioteca.

        ::: indicacion
        1.  Seleccionar el menú .

        2.  En el cuadro de diálogo que aparece seleccionar la variable
            en el campo e introducir `si` en el campo .

        3.  En la solapa introducir $0.99$ en el campo y hacer clic en
            el botón .
        :::

    3.  ¿Qué interpretación tiene dicho intervalo? ¿Cómo es su
        precisión?

    4.  ¿Qué tamaño muestral sería necesario para obtener una estimación
        del porcentaje de alumnos que utilizan regularmente la
        biblioteca con un margen de error de un 1% y una confianza del
        95%?

        ::: indicacion
        1.  Seleccionar el menú .

        2.  En el cuadro de diálogo que aparece introducir la proporción
            muestral en el campo , el nivel de significación deseado, en
            este caso $0.05$, en el campo , el margen de error deseado,
            en este caso $0.01$, en el campo , y hacer clic en el botón
            .
        :::

4.  El Ministerio de Sanidad está interesado en la elaboración de un
    intervalo de confianza para la proporción de personas mayores de 65
    años con problemas respiratorios que han sido vacunadas en una
    determinada ciudad. Para ello, después de preguntar a 200 pacientes
    mayores de 65 años con problemas respiratorios en los hospitales de
    dicha ciudad, 154 responden afirmativamente.

    1.  Calcular el intervalo de confianza al 95% para la proporción de
        pacientes vacunados.

        ::: indicacion
        1.  Seleccionar el menú .

        2.  En el cuadro de diálogo que aparece marcar la opción ,
            introducir 154 en el campo , introducir 200 en el campo y
            hacer clic en el botón .
        :::

    2.  Si entre los objetivos del Ministerio se encontraba alcanzar una
        proporción de al menos un 70% de vacunados en dicho colectivo,
        ¿se puede concluir que se han cumplido los objetivos? Justificar
        la respuesta.

## Ejercicios propuestos

1.  Para determinar el nivel medio de colesterol (en mg/dl) en la sangre
    de una población, se realizaron análisis sobre una muestra de 8
    personas, obteniéndose los siguientes resultados:

    ::: center
    196
    :::

    Hallar los intervalos de confianza para la media del nivel de
    colesterol con niveles de significación $0.1$, $0.05$ y $0.01$. ¿Se
    puede afirmar que el nivel de colesterol medio de la población está
    por debajo de 210 mg/dl?

2.  Para tratar un determinado síndrome neurológico se utilizan dos
    técnicas $A$ y $B$. En un estudio se tomó una muestra de 60
    pacientes con dicho síndrome y se le aplicó la técnica $A$ a 25 de
    ellos y la técnica $B$ a los 35 restantes. De los pacientes tratados
    con la técnica $A$, 18 se curaron, mientras que de los tratados con
    la técnica $B$, se curaron 21. Calcular un intervalo de confianza
    del 95% para la proporción de curaciones con cada técnica. ¿Qué
    intervalo es más preciso?

3.  A las siguientes elecciones locales en una ciudad se presentan tres
    partidos: A, B y C. Con el objetivo de hacer una estimación sobre la
    proporción de voto que cada uno de ellos obtendrá, se realiza una
    encuesta en la que responden 300 personas, de las cuales 60 piensan
    votar a A, 80 a B, 90 a C, 15 en blanco y 55 abstenciones. Calcular
    un intervalo de confianza para la proporción de votos, sobre el
    total del censo, de cada uno de los partidos que se presentan.

4.  El conjunto de datos del paquete , contiene información sobre una
    muestra de 320 recién nacidos en un hospital durante un año que
    cumplieron el tiempo normal de gestación. Se pide:

    1.  Calcular el intervalo de confianza del 99% para el peso medio de
        los recién nacidos. ¿Entre qué valores estará el peso medio?

    2.  Calcular el intervalo de confianza para la puntuación media del
        Apgar al minuto de nacer y compararlo con el de la puntuación
        Apgar a ls 5 minutos. ¿Existen diferencias significativas entre
        las medias de ambas puntuaciones?

    3.  Calcular el intervalo de confianza para el porcentaje de niños
        con peso menor o igual que 2.5 Kg en el grupo de las madres que
        han fumado durante el embarazo y en el de las que no.
