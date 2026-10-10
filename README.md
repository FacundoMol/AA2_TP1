# Trabajo Práctico N° 1: Redes Neuronales Feed Forward y Convolucionales

**Institución:** FCEIA - UNR  
**Carrera:** Tecnicatura Universitaria en Inteligencia Artificial (TUIA)  
**Asignatura:** Aprendizaje Automático II  

## 👥 Integrantes del Grupo

* Facundo Molina
* Gabriel Soda
* Jonathan Gallardo
* Martín Facundo Lapolla

## 📝 Descripción del Proyecto

Este repositorio contiene la resolución del primer trabajo práctico de la materia. El objetivo principal es el diseño, entrenamiento y evaluación de redes neuronales aplicadas a cuatro problemas de distinta naturaleza, justificando las decisiones de arquitectura, preprocesamiento y optimización.

El proyecto se divide en los siguientes cuatro problemas abordados en Jupyter Notebooks individuales:

1. **Problema 1: Clasificación Binaria**  
   Predicción de riesgo de accidente cerebrovascular (ACV) a partir de datos clínicos y demográficos usando un Perceptrón Multicapa (MLP).
2. **Problema 2: Clasificación Multiclase**  
   Reconocimiento de dígitos manuscritos (dataset MNIST) a partir de imágenes en escala de grises utilizando un MLP.
3. **Problema 3: Regresión**  
   Predicción de la rentabilidad (Profit) de transacciones comerciales en base a características logísticas y de producto mediante un MLP.
4. **Problema 4: Redes Convolucionales (CNN)**  
   Clasificación de razas de perros entrenando una Red Neuronal Convolucional desde cero (sin transfer learning), experimentando con distintas arquitecturas (bloques profundos, residuales, Inception) y técnicas de regularización/Data Augmentation.

## 📂 Estructura del Repositorio

* `Problema_1.ipynb`: Resolución de la predicción de ACV.
* `Problema_2.ipynb`: Resolución de clasificación MNIST.
* `Problema_3.ipynb`: Resolución de predicción de rentabilidad.
* `Problema_4.ipynb`: Resolución de clasificación de razas de perros con CNN.
* `Informe_TP1.pdf`: Informe detallado con decisiones de diseño, análisis de resultados y conclusiones.
* `requirements.txt`: Listado de dependencias necesarias para ejecutar el código.

## ⚙️ Instalación y Requisitos

Para reproducir los experimentos, se recomienda crear un entorno virtual e instalar las dependencias listadas en el archivo `requirements.txt`. El proyecto utiliza principalmente `PyTorch`, `NumPy`, `Pandas` y `Scikit-learn`.

```bash
# Clonar el repositorio
git clone https://github.com/FacundoMol/AA2_TP1
cd AA2_TP1

# Crear un entorno virtual (opcional pero recomendado)
python -m venv env
source env/bin/activate  # En Linux/Mac
env\Scripts\activate     # En Windows

# Instalar las dependencias
pip install -r requirements.txt
```

## 📊 Reproducibilidad
Todos los notebooks incluyen la fijación de semillas aleatorias al inicio de cada experimento para garantizar que los resultados, métricas y curvas de entrenamiento puedan ser reproducidos con exactitud.