# Proyecto de Clasificación del Nivel de Fermentación de Granos de Cacao

![Banner](/BannerThunders.jpg)

--- 
## Autores
- Carlos David Barrera Rangel - 2230056, Fernando Vargas Quintero - 2200347

---

## Objetivo

Determinar el nivel de fermentación de un grano de cacao (Bueno, Parcial o Malo) a partir de una imagen del mismo.

---

## Objetivos Específicos
- Clasificar un grano de cacao en Bueno, Parcial o Malo.
- Extraer la información más relevante de cada imagen (características de color en HSV y RGB).
- Entrenar y evaluar distintos modelos de clasificación supervisada.
- Comparar el desempeño de los distintos modelos implementados.
- Explorar la estructura de los datos con técnicas no supervisadas (clustering y reducción de dimensionalidad).

---

## Dataset

Se usó un dataset propio con imágenes de granos de cacao de 19 escenas distintas.

**Características:**
- Formato: imágenes digitales (JPEG) organizadas en una carpeta por escena ("Escena 1", "Escena 2", ...).
- Contenido de cada escena: la foto general ("cacao.jpg"), la imagen de etiquetas de fermentación ("label_fermentation.jpg"), archivo YOLO ("cacao.txt") y la carpeta "Fotos" con la imagen recortada de cada semilla.
- Volumen: 938 granos etiquetados en total (las no etiquetadas se descartaron).
- Clasificación: 3 niveles de fermentación (Bueno, Parcial y Malo).


---

## Modelos
Los métodos evaluados en este proyecto fueron:

**Supervisados**
- Regresión Logística.
- Gaussian Naive Bayes.
- Decision Tree.
- Random Forest.
- Support Vector Classifier (SVC).
- Deep Learning.

**No supervisados**
- K-means.
- DBSCAN.
- Agglomerative Clustering.
- PCA.
- t-SNE.
  
Se evaluaron con matriz de confusión y métricas por clase, junto con promedios macro (precisión, sensibilidad y F1), por el desbalance entre clases
---
## Enlaces
- Repositorio de Github: [Clasificacion-de-granos-de-cacao](https://github.com/CarlosBarreraR/Clasificacion-de-granos-de-cacao).
- Dataset: [Imágenes de granos de cacao (Google Drive)](https://drive.google.com/drive/folders/1IDlLL4ZjDn5a1bad0DYRnIsEuwhbYaAW?usp=sharing).
- Slides: [Canva](https://canva.link/rgqyci5v50uvo26).
- Video del proyecto: [Youtube]().
---
