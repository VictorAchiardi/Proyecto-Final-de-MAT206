# Preguntas a evaluar del Proyecto Final de MAT206.

# Pregunta 1.
Considere los datos disponibles en el sitio: https://cmustatistics.github.io/data-repository/money/ ames-housing.html\#ames-housing-csv acerca de los precios de las casas en venta en Ames, Iowa, USA. Este conjunto de datos posee los precios de 2930 casas en esa localidad. La variable de interés se denomina SalePrice y corresponde a la última columna de la base de datos.

    a) Realice un análisis descriptivo para la variable SalePrice. ¿Qué patrones observa? 
    
    b) Ajuste una distribución de probabilidad a los datos de la variable SalePrice. Justifique su respuesta. 
    
    c) Grafique el histograma y la curva de densidad ajustada en un mismo gráfico. 
    
    d) Aplique un test de bondad de ajuste para determinar si la distribución es apropiada. 
    
    e) En el condado de Ames, ¿cuál es la probabilidad de que una casa cueste más de 200,000 US dollars? 
    
    f) ¿Cuál es el valor esperado del precio de las casas a la venta en Ames? 
    
    g) Determine un intervalo de confianza del 95\% para la media de la distribución.

# Pregunta 2.
Considera el conjunto de datos sobre las magnitudes de terremotos cerca de Fiji que están disponibles en el siguiente sitio https://www.stat.cmu.edu/~larry/all-of-nonpar/data.html.

    a) Estime la función de distribución F(x). 
    
    b) Construya un intervalo de confianza del 95\% para las bandas (envelopes) de F. 
    
    c) Encuentre un intervalo de confianza del 95\% para F(4,9)- F(4,3).
    
# Pregunta 3.
Los siguientes datos han sido usados para ilustrar las técnicas de bootstrap por Bradley Efron, el inventor de esta técnica. Los datos consisten en dos variables: LSAT (prueba para ingresar a la escuela de derecho en USA) y el GPA.

LSAT: 576 , 635 , 558 , 578 , 666 , 580 , 555 , 661 , 651 , 605 , 653 , 575 , 545 , 572 , 594

GPA: 3.39 , 3.30 , 2.81 , 3.03 , 3.44 , 3.07 , 3.0 , 3.43 , 3.36 , 3.13 , 3.12 , 2.74 , 2.76 , 2.88 , 3.96

Cada punto es de la forma $X_i = (Y_i ,Z_i)$ donde $Y_i = \text{LSAT}_i$ y $Z_i = \text{GPA}_i$.

    a) Calcule el coeficiente de correlación entre las variables LSAT y GPA. 
    
    b) Calcule el error estándar del coeficiente de correlación usando Jackknife.
    
    c) Calcule el error estándar del coeficiente de correlación usando Bootstrap. 
    
    d) Compare los resultados encontrados en b) y c) con la varianza asintótica del coeficiente de correlación cuando se asume normalidad bivariada.
