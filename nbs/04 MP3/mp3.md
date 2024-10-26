### MP·: Análisis de Reseñas de iPhone Utilizando Técnicas de PLN

**Objetivo**: La actividad consiste en analizar un conjunto de datos de reseñas de iPhone y aplicar varias técnicas de procesamiento de lenguaje natural (PLN) para clasificar las reseñas como positivas o negativas. Deberán implementar un modelo de clasificación y evaluar su rendimiento utilizando las técnicas de PLN proporcionadas.

### Instrucciones:

#### Parte 1: Carga y Exploración de Datos
1. **Carga del Conjunto de Datos**:
   - Carga el archivo `iphone.csv` en tu entorno de trabajo.
   - Realiza una exploración inicial de los datos, identificando:
     - La columna que contiene el texto de las reseñas.
     - La columna que indica si la reseña es positiva o negativa.

2. **Descripción Inicial de los Datos**:
   - Describe la cantidad de reseñas presentes.
   - Revisa el balance de clases (¿hay más reseñas positivas que negativas?).

#### Parte 2: Preprocesamiento de Texto
3. **Preprocesamiento del Texto**:
   - Aplica las siguientes técnicas de PLN al texto de las reseñas:
     - **Tokenización**: Convierte las reseñas en una lista de palabras individuales.
     - **Stemming o Lematización**: Reduce las palabras a su raíz (stemming) o a su forma base (lematización).
     - **Eliminación de Stop Words**: Remueve palabras irrelevantes como "el", "la", "en".

   - Comenta brevemente cómo estas técnicas ayudan a limpiar y preparar el texto para el análisis.

#### Parte 3: Representación del Texto con Bag of Words
4. **Bag of Words (BoW)**:
   - Convierte las reseñas preprocesadas en una matriz de características utilizando la técnica de **Bag of Words (BoW)**.
   - Explica cómo funciona BoW y su importancia para convertir texto en una representación numérica que pueda ser utilizada por los modelos de aprendizaje automático.

#### Parte 4: Implementación de Clasificadores
5. **Clasificador Naive Bayes**:
   - Entrena un **Clasificador Naive Bayes** con los datos procesados y representados mediante BoW.
   - Evalúa su rendimiento usando métricas como la precisión, el recall y el F1-score.
   - Comenta los resultados obtenidos.

6. **Regresión Logística**:
   - Alternativamente, entrena un modelo de **Regresión Logística** con los mismos datos.
   - Compara su rendimiento con el clasificador Naive Bayes utilizando las mismas métricas.
   - Reflexiona sobre cuál de los dos modelos tuvo un mejor desempeño y por qué.

#### Parte 5: Análisis y Conclusión
7. **Análisis de Resultados**:
   - Realiza un análisis comparativo de los dos modelos entrenados (Naive Bayes y Regresión Logística).
   - Discute qué modelo proporciona mejores predicciones para este conjunto de datos.
   - ¿Qué otros métodos de mejora sugerirías para el preprocesamiento o para los modelos de clasificación?

8. **Entrega**:
   - Debes entregar un **notebook Jupyter + su despliegue HTML** que incluya todo el código desarrollado, junto con los comentarios explicativos.
   - Un informe final breve donde presentes el análisis de los resultados y las conclusiones de la tarea.
   - Subir a Campus Virtual (sección evaluaciones).
   - Fecha de entrega: 25 de Octubre, 2024; 18:00 hrs.

### Criterios de Evaluación:
- Correcta implementación de las técnicas de preprocesamiento.
- Adecuada representación del texto usando Bag of Words.
- Implementación y evaluación de los clasificadores.
- Claridad en el análisis de los resultados y conclusiones.

### Herramientas:
- Python (con bibliotecas como `nltk`, `scikit-learn`, `pandas`, `matplotlib`).
