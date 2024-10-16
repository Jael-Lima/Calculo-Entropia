# Calculo-Entropia


## Equipo:
### Freda Maria Perez Novelo
### Brisa Jael Lima Arenas



## Introducción

### Este trabajo tiene como objetivo desarrollar un programa que permita analizar un conjunto de datos mediante el cálculo de probabilidades de clases y entropía. La entropía mide el grado de incertidumbre en un sistema, siendo una herramienta esencial para la compresión y clasificación de datos, en la teoría de la información. A través de este cálculo,  se busca identificar las clases de un conjunto de datos, calcular sus probabilidades y determinar la entropía del sistema, proporcionando una perspectiva cuantitativa sobre la diversidad o el orden en los datos.

## Metodología
###  1. Obtención del repositorio de datos
### Se seleccionó un repositorio de datos abierto para facilitar el acceso a un conjunto de información estructurada y con posibilidad de replicación. Este repositorio fue evaluado en términos de relevancia y aplicabilidad a la tarea, priorizando los que tuvieran múltiples clases para un análisis de entropía significativo, pensamos en la música, porque si buscábamos un buen repositorio, podríamos encontrarnos con respuestas diferentes, más que nada al ser un top 50 de canciones en spotify podíamos tener la certeza de que con la variedad de géneros musicales y su diferente bailabilidad, incluso los beats por minuto harían una diferencia y  tendríamos diferentes opciones.

### 2. Preparación de los datos
### Antes de proceder al cálculo de probabilidades y entropía, los datos fueron sometidos a un proceso de limpieza y preparación. Esto incluyó la eliminación de valores nulos, la normalización de formatos y, si fuera necesario, la transformación de variables categóricas en representaciones numéricas para el cálculo estadístico.

### 3. Determinación del objetivo de probabilidad
### Se definió el objetivo del análisis probabilístico: identificar la probabilidad de cada clase dentro de la variable de interés, lo cual permitirá obtener un panorama claro de la distribución de clases en el conjunto de datos y la probabilidad asociada a cada una de ellas. Nos queríamos centrar en los datos calculables, sin dejar clases como “nombre de las canciones” o “género” para poder también mostrar datos no numéricos, que fueran variados. 

### 4. Identificación de clases
### Se procedió a identificar y enumerar las clases presentes en el conjunto de datos, asignando a cada una un valor probabilístico para el cálculo subsecuente de la entropía, por ende pusimos 4 clases en la identificación.

### 5. Cálculo de las probabilidades de las clases
### Para cada clase identificada en las variables género, bailabilidad y beats por minuto, se calculó su frecuencia relativa dividiendo el número de ocurrencias de cada clase por el total de instancias, obteniendo así la probabilidad de cada una.

### 6. Cálculo de la entropía del sistema
### Utilizando las probabilidades obtenidas, se aplicó la fórmula de la entropía de Shannon. La entropía del sistema proporciona una medida de la diversidad o incertidumbre, ofreciendo una evaluación cuantitativa de la dispersión de las clases en el conjunto de datos.


# Cálculo y análisis

### Para calcular la entropía del sistema, se identificaron y analizaron tres variables clave del conjunto de datos: Género, Bailabilidad y Beats por Minuto (BPM). Estas variables permiten obtener una medida de la distribución y diversidad en el conjunto de datos.

### 1. Género:
### Se calculó la frecuencia de cada género en el conjunto de datos y, a partir de ello, la probabilidad de cada clase (género) dividiendo su frecuencia entre el total de canciones.
### Con estas probabilidades, se aplicó la fórmula de entropía de Shannon: 
![Formula Entropia](https://scontent.fcun1-1.fna.fbcdn.net/v/t1.6435-9/41222078_2006427969424221_485605469390372864_n.png?_nc_cat=109&ccb=1-7&_nc_sid=f798df&_nc_eui2=AeFT4Di-lWvtkEWW0OkzaG40sGLwAltjmQiwYvACW2OZCIvtea0g4mB80jAo_TiANlLISk5OwBIedRs1Od8WwP_k&_nc_ohc=ObHcWAeYQjQQ7kNvgFelF9X&_nc_zt=23&_nc_ht=scontent.fcun1-1.fna&_nc_gid=A3vgGn2bv88qgDCeR3RyBVy&oh=00_AYDbUmyRjXuFoa6iJiWodDQjQBLVTrSqhxKlAP4umK-amQ&oe=67366183)

###   donde px representa la probabilidad de cada género.

### 2. Bailabilidad:
### De igual manera, se calculó la frecuencia de cada nivel de bailabilidad y luego su probabilidad relativa.
### Con las probabilidades obtenidas, se calculó la entropía utilizando la misma fórmula para estimar la dispersión y diversidad de los niveles de bailabilidad.

### 3. Beats por Minuto (BPM):
### Se analizó la frecuencia de cada valor de BPM en el conjunto de datos y se calculó la probabilidad de ocurrencia de cada uno.
### Posteriormente, se aplicó la fórmula de entropía para evaluar la variabilidad y distribución de esta métrica.

## Resultados

### Entropía del Género: La entropía calculada para el género fue de 4.03. Esto indica que existe una variedad considerable de géneros en el conjunto de datos, lo cual muestra diversidad en las preferencias musicales representadas.
  
### Entropía de Bailabilidad: La entropía calculada para bailabilidad fue de 4.72, lo cual refleja una alta variabilidad en los niveles de bailabilidad de las canciones. Esto sugiere que hay una diversidad de canciones en cuanto a su potencial de ser "bailables".
  
### Entropía de Beats por Minuto (BPM): Con una entropía de 4.74, el BPM muestra una distribución amplia de ritmos. Esto indica que el conjunto de canciones tiene una variación considerable en términos de tempo, lo cual puede atraer a una audiencia con diferentes gustos.

## Conclusiones

### El análisis de entropía aplicado al conjunto de datos muestra que existe una gran diversidad tanto en los géneros, los niveles de bailabilidad y los BPM de las canciones analizadas. La alta entropía en las variables clave sugiere que las canciones en el conjunto no se concentran en una categoría específica, sino que presentan una variedad de características musicales que podrían interesar a una amplia audiencia. Esta variabilidad, medida a través de la entropía, es esencial para comprender la amplitud de opciones dentro del Top 50 de Spotify y puede ser útil en la personalización de listas de reproducción para adaptarse a distintos gustos y contextos musicales.



## Referencias 
### Serrano, L. (2018, 26 octubre). Shannon Entropy, Information Gain, and Picking Balls from Buckets. Medium. https://medium.com/udacity/shannon-entropy-information-gain-and-picking-balls-from-buckets-5810d35d54b4 
### Hottest Spotify Hits. (2023).  Most Streamed Spotify Songs 2023 https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023
