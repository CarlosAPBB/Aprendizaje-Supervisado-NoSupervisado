# Clasificación de Alimentos con Aprendizaje Supervisado y No Supervisado

Este proyecto aplica algoritmos de **Aprendizaje Supervisado** y **Aprendizaje No Supervisado** para analizar un conjunto de datos de alimentos, clasificándolos según sus características nutricionales.

## Tabla de Contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Conjunto de Datos](#conjunto-de-datos)
3. [Algoritmos Utilizados](#algoritmos-utilizados)
4. [Requisitos](#requisitos)
5. [Instalación](#instalación)
6. [Uso](#uso)
7. [Resultados](#resultados)
8. [Licencia](#licencia)

## Descripción del Proyecto

Este proyecto explora un conjunto de datos nutricionales utilizando algoritmos de **aprendizaje supervisado** y **no supervisado**. El objetivo es categorizar alimentos en función de su contenido de grasa y aplicar un modelo de **Logistic Regression** para predecir categorías, así como utilizar **K-means** para la clasificación no supervisada de los alimentos.

## Conjunto de Datos

El conjunto de datos proviene de Kaggle y contiene 722 entradas con 37 columnas. Cada fila representa un alimento, y cada columna proporciona información nutricional detallada, como valor calórico, grasas, carbohidratos, proteínas, vitaminas, minerales, etc.

Puedes acceder al conjunto de datos original [aquí](https://www.kaggle.com/datasets/utsavdey1410/food-nutrition-dataset).

## Algoritmos Utilizados

### 1. **Logistic Regression (Aprendizaje Supervisado)**

-   Se utilizó para clasificar los alimentos en categorías según su contenido en grasas: **Bajo en grasas**, **Moderado en grasas**, y **Alto en grasas**.
-   Este modelo predice la probabilidad de que un alimento pertenezca a una de estas categorías basado en sus características nutricionales.

### 2. **K-means (Aprendizaje No Supervisado)**

-   Utilizado para agrupar alimentos en clusters basados en tres características nutricionales: **Grasas**, **Carbohidratos** y **Proteínas**.
-   El algoritmo clasifica los alimentos en 3 clusters sin que haya etiquetas definidas previamente.

## Requisitos

Para ejecutar el proyecto, necesitarás las siguientes librerías:

-   `numpy`
-   `pandas`
-   `matplotlib`
-   `scikit-learn`
-   `mpl_toolkits`

## Instalación

1. Clona el repositorio en tu máquina local:
    ```bash
    git clone https://github.com/tu-usuario/tu-repo.git
    ```
    
2. Navega a la carpeta del proyecto:
    ```bash
    cd tu-repo
    ```
    
3. Instala los paquetes necesarios:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

1. Abre el archivo `notebook.ipynb` en Jupyter Notebook o JupyterLab.
2. Ejecuta las celdas para:
   - Explorar el conjunto de datos.
   - Entrenar el modelo de regresión logística.
   - Aplicar el algoritmo K-means y visualizar los clusters.
3. Modifica el código según tus necesidades.

## Resultados

- **Aprendizaje Supervisado**: Utilizando **Logistic Regression**, se logró predecir con precisión la categoría de los alimentos según su contenido en grasas.
- **Aprendizaje No Supervisado**: Con **K-means**, se observaron agrupaciones de alimentos en tres clusters, lo que permitió identificar patrones de similitud entre alimentos sin necesidad de etiquetas previas.
