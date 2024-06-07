## PT_ML

### Ejercicio 1. Explica la diferencia entre aprendizaje supervisado y no supervisado. Proporciona ejemplos de algoritmos para cada tipo.

En el aprendizaje supervisado se enseña o entrena al algoritmo a partir de datos que ya vienen etiquetados con la respuesta correcta. El objetivo del modelo es aprender a mapear entradas a salidas basándose en estos datos etiquetados para poder hacer predicciones sobre datos nuevos. Ejemplos de algoritmos:
- Regresión Lineal
- Regresión Logística
- Máquinas de vectores de soporte (SVM)
- Arboles de decisión 
- Redes Neuronales

Mientras que el aprendizaje no supervisado, el algoritmo es entrenado usando un conjunto de datos que no tiene ninguna etiqueta, en este caso, nunca se le dice al algoritmo lo que representan esos datos. La idea es que el algoritmo pueda encontrar por sí solo patrones que ayuden a entender el conjunto de datos o a encontrar anomalías en los datos.

Ejemplo de algoritmos:
- Clustering (agrupamiento): K-Means, Hierarchical Clustering
- Análisis de componentes principales (PCA)
- Algoritmo de aprendizaje (EM)
- Mapas autoorganizados (SOM)

### Ejercicio 2. ¿Qué es el overfitting y cómo se puede prevenir?

Es cuando el modelo se ajusta excesivamente a los datos de entrenamiento y tiene dificultad para generalizar y hacer predicciones precisas sobre nuevos datos.
Entre las técnicas para prevenir son: usar técnicas de validación cruzada, aumentar datos (asegurarnos que sean datos limpios y libres de inconsistencias), elegir modelos más simples o reducir parámetros.


### Ejercicio 3. Describe brevemente el algoritmo de Random Forest y menciona sus principales ventajas y desventajas.

El algoritmo Random Forest (bosque aleatorio) es un método de aprendizaje automático supervisado utilizado tanto para tareas de clasificación como de regresión. Es una técnica de conjunto que combina múltiples árboles de decisión individuales para generar una predicción más robusta y precisa.

- El algoritmo toma “n” números de registros aleatorios del conjunto de datos.
- Se construyen árboles de decisión individuales para cada muestra.
- Cada árbol de decisión generará una salida.
- El resultado final depende de la mayoría o el promedio para la clasificación y la regresión, respectivamente.

 ***Ventajas:***
- Alta precisión
- Robustez frente al sobreajuste.
- Manejo eficaz de características
- Eficiencia en grandes conjuntos de datos
- Poca necesidad de ajuste de hiperparámetros.
  
***Desventajas:***
- Puede requerir muchísimo tiempo de entrenamiento.
- No funciona bien con datasets pequeños.
- Pérdida de interpretación.
- Menos efectivo con datos dispersos

### Ejercicio 4. ¿Qué es una red neuronal convolucional (CNN) y para qué tipo de tareas es más adecuada?

Es un tipo de red neuronal especialmente diseñada para procesar datos con una estructura de cuadrícula, como las imágenes. Son muy efectivas para tareas de visión por computadora debido a su capacidad para capturar las características espaciales y temporales de los datos, es utilizada principalmente para el reconocimiento y procesamiento de imágenes, clasificación, detección de objetos, captura de imágenes médicas, reconocimiento facial.

### Ejercicio 5. ¿Qué es la limpieza de datos y por qué es importante en el proceso de análisis de datos? Proporciona ejemplos de técnicas de limpieza de datos.
Es el proceso de detectar y corregir (o eliminar) cualquier error o inconsistencia en los datos. Su objetivo principal es mejorar la calidad de los datos, asegurando que la información sea precisa, consistente y utilizable.
Entre las técnicas de limpieza son:

- Eliminación de duplicados
- manejo de datos faltantes
- Corrección de datos incorrectos 
- Manejo de valores atípicos
- Validar la coherencia de los datos
- Transformación de datos.

### Ejercicio 6. Explica qué es el web scraping y menciona algunas herramientas populares para realizarlo.
El web scraping es el proceso de recopilar datos web estructurados de forma automatizada. Varían ampliamente en diseño y complejidad, dependiendo del proyecto. Una parte importante de cada scraper son los localizadores de datos (o selectores) que se utilizan para encontrar los datos que se desean extraer del archivo HTML. 

Herramientas y bibliotecas: las bibliotecas de Python como Beautiful Soup, Scrapy y Selenium son opciones populares para el web scraping.
<br>
### Ejercicio 7. Describe los pasos básicos para extraer datos de una página web y transformarlos en un formato utilizable para el análisis de datos.

***Pasos básicos según (Persson 2019)***
- Paso 1: Acceso al sitio web a través del protocolo HTTP. Obtener la página HTML como respuesta.

- Paso 2: Etapa de extracción. Utilizando técnicas de expresiones regulares, las bibliotecas de parseo HTML y las consultas XPath son utilizadas en esta etapa.

- paso 3: Etapa de transformación. Los datos son convertidos en un formato estructurado y almacenados para un posterior análisis.
