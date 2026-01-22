# 🔬 Roast Coffee Agtron - Experimentos y Modelos

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

Este repositorio contiene el código fuente, los experimentos y los cuadernos (notebooks) desarrollados para el análisis de tostado de café y la predicción de valores Agtron mediante visión por computadora e inteligencia artificial.

Este trabajo forma parte de la fase experimental del proyecto de titulación para la clasificación y validación de granos de café.

## 📂 Estructura del Repositorio

El proyecto está organizado en diferentes módulos experimentales:

*   **`Modelo Binario coffe vs no Coffee/`**: Contiene el entrenamiento de un modelo de clasificación binaria para distinguir entre imágenes que contienen granos de café y las que no (filtrado inicial).
*   **`Prueba de laboratorio/`**: Notebooks utilizados para validaciones con datos reales o pruebas controladas en entorno de laboratorio.
*   **`exp2/` y `exp4/`**: Iteraciones de experimentos con diferentes arquitecturas, preprocesamiento de imágenes o hiperparámetros para mejorar la precisión del cálculo Agtron. exp2 corresponde al entrenamiento de cada modelo sin optimización de hiperparámetros Por otro lado exp4, muestra el entrenamiento de los modelos con la optimización de hiperparámetros realizado con el framework Optuna. 

## 🛠️ Tecnologías y Librerías

El proyecto ha sido desarrollado en **Python** utilizando el entorno de **GoogleColab y Kaggle Notebook**. Las principales librerías utilizadas incluyen (pero no se limitan a):

*   **TensorFlow / Keras & PyTorch**: Para la creación y entrenamiento de redes neuronales.
*   **OpenCV (cv2)**: Para el procesamiento digital de imágenes y extracción de características de color.
*   **Pandas & NumPy**: Para la manipulación de datos numéricos y estructuras de datos.
*   **Matplotlib / Seaborn**: Para la visualización de resultados y gráficas de entrenamiento.
*   **Scikit-learn**: Para métricas de evaluación y algoritmos de machine learning clásicos.

## 🚀 Cómo ejecutar los Notebooks

Para replicar los experimentos o ejecutar los notebooks en tu máquina local:

1.  **Clonar el repositorio**
    ```bash
    git clone https://github.com/JavierSarango/roast-coffee-agtron.git
    cd roast-coffee-agtron
    ```

2.  **Crear un entorno virtual (Recomendado)**
    ```bash
    python -m venv venv
    # En Windows:
    venv\Scripts\activate
    # En Mac/Linux:
    source venv/bin/activate
    ```

3.  **Instalar las dependencias**
    *(Nota: Si tienes un archivo requirements.txt, úsalo. Si no, instala las básicas manualment)*
    ```bash
    pip install jupyter notebook tensorflow opencv-python pandas matplotlib scikit-learn
    ```

4.  **Iniciar Jupyter**
    ```bash
    jupyter notebook
    ```

5.  **Explorar**: Abre los archivos `.ipynb` en tu navegador y ejecuta las celdas secuencialmente.

## 📊 Resultados

El objetivo de estos scripts es:
1.  Preprocesar imágenes de muestras de café.
2.  Segmentar los granos de café del fondo.
3.  Calcular o predecir la categoría **Agtron** (grado de tostado) basado en el color y textura.
4.  Validar si la imagen corresponde efectivamente a café.


---
**Autor:** [JavierSarango](https://github.com/JavierSarango)
