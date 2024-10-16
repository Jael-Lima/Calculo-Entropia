# Calculo-Entropia

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
!entropia [https://scontent.fcun1-1.fna.fbcdn.net/v/t1.6435-9/41222078_2006427969424221_485605469390372864_n.png?_nc_cat=109&ccb=1-7&_nc_sid=f798df&_nc_eui2=AeFT4Di-lWvtkEWW0OkzaG40sGLwAltjmQiwYvACW2OZCIvtea0g4mB80jAo_TiANlLISk5OwBIedRs1Od8WwP_k&_nc_ohc=ObHcWAeYQjQQ7kNvgFelF9X&_nc_zt=23&_nc_ht=scontent.fcun1-1.fna&_nc_gid=A3vgGn2bv88qgDCeR3RyBVy&oh=00_AYDbUmyRjXuFoa6iJiWodDQjQBLVTrSqhxKlAP4umK-amQ&oe=67366183]


