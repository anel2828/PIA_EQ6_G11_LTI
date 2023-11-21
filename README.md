# PIA_EQ6_G11_LTI
El programa del caso de la Residencia en Australia.
El caso por resolver es el siguiente:
El Instituto de Migración de Australia tiene un algoritmo de calificación de familias que solicitan la residencia, en caso de que toda la familia decida migrar. No es sorpresa que el puntaje de las familias esté en función de la probabilidad de contribuir con el aumento demográfico de la nación, y con los oficios que tienen mucha demanda y poca oferta.
La aplicación pregunta primero si la familia es monoparental (un solo padre) o biparental (ambos padres). Dependiendo de la respuesta, preguntará los datos de los padres; si es monoparental solo pregunta los datos del único progenitor; si es biparental, pregunta los datos de ambos progenitores.
Los datos que se preguntan de los progenitores son: Sexo (M: Masculino; F: Femenino; N: No binario). Se pregunta la fecha de nacimiento. Se pregunta el grado académico (P: Postgraduado; U: Universitario; T: Técnico; N: Ninguno). Se pregunta si tiene alguno de los 10 oficios requeridos en el país (Se enumerarán los oficios, contenidos en una lista, al momento de preguntar. La respuesta debe ser S o N, correspondiente a Sí o No).
Luego se pregunta cuántos hijos hay en la familia. Dependiendo de la respuesta, se preguntan datos específicos de los hijos.
Los datos que se preguntan de cada hijo son: Sexo (M: Masculino; F: Femenino; N: No binario). Se pregunta la fecha de nacimiento.
Un parámetro importante es la edad fértil de las mujeres. Se considera la edad fértil deseable entre 20 y 35 años. Por cada año dentro de la edad fértil, se suma un punto. Por ejemplo: Si hoy es 9/nov/2023, y una de las progenitoras nació el 1/ene/2000, tendrá 23 años cumplidos, por lo cual se considera que le restan (15-(23-20)) = 12. Si tienen una hija, y tiene 5 años, aportará 35 puntos.
Cada vez que el sexo de los progenitores sea F, otorgará puntos, de acuerdo con los puntos otorgados en el párrafo anterior.
Si los progenitores tienen un oficio deseado (en la lista), proporcionará 8 puntos adicionales. Si tienen postgrado, suman 5 puntos adicionales; título universitario, suma 3 puntos.
Cada progenitor suma 6 puntos. Cada hijo suma 8 puntos.
Hacer el programa que capture toda esta información, y calcule el puntaje.
