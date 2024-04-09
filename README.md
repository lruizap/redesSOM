# Proyecto de Clasificación de Vinos con SOM y MiniSom

---

Este proyecto utiliza la biblioteca MiniSom para entrenar una red SOM (Self-Organizing Map) y clasificar vinos en el conjunto de datos de vinos famoso del repositorio UCI Machine Learning. El conjunto de datos contiene resultados de un análisis químico de vinos cultivados en la misma región en Italia pero derivados de tres diferentes cultivares. La tarea consiste en clasificar estos vinos en sus respectivos cultivares basándose en su composición química.

## Requisitos

- Python 3.x
- Bibliotecas: `numpy`, `pandas`, `scikit-learn`, `minisom`, `matplotlib`

## Pasos del Proyecto

El proyecto está dividido en varias partes:

### 1. Preparación de Datos

- Carga del conjunto de datos de vinos utilizando `sklearn.datasets.load_wine()`.
- Estandarización de los datos para tener una media de 0 y una desviación estándar de 1.

### 2. Entrenamiento de la SOM

- Inicialización de la SOM utilizando MiniSom.
- Entrenamiento de la SOM con los datos estandarizados.

### 3. Visualización y Análisis

- Creación de un mapa de impactos para visualizar la frecuencia de selección de cada neurona como la mejor neurona ganadora (BMU).
- Generación de planos de componentes para cada característica química en el conjunto de datos.
- Análisis de la agrupación y clasificación de los vinos en la SOM.

### 4. Reporte y Conclusión

- Interpretación de cómo las diferentes características químicas influencian la agrupación de los vinos.
- Reflexión sobre los desafíos enfrentados al trabajar con SOM y cómo se superaron.
- Evaluación de la efectividad de la SOM para clasificar los vinos según sus características químicas y sugerencias para futuros experimentos.

## Cómo Ejecutar

1. Instala las bibliotecas necesarias mencionadas en los requisitos.
2. Ejecuta el script `redesSOM.ipynb` para ejecutar el proyecto.

## Archivos Incluidos

- `redesSOM.ipynb`: Código Python para el proyecto.
- `README.md`: Este archivo que contiene la descripción del proyecto.
- `LICENSE`: Licencia para el uso del código.
