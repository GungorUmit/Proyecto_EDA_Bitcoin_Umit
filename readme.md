# Exploratory Data Analysis - Celiac Disease

Este proyecto realiza un Análisis Exploratorio de Datos (EDA) sobre un dataset clínico relacionado con la **enfermedad celíaca**.  

La enfermedad celíaca es una enfermedad autoinmune grave que ocurre en personas genéticamente predispuestas donde la ingestión de gluten provoca daños en el intestino delgado. Se estima que afecta a 1 de cada 100 personas en todo el mundo, pero solo alrededor del 30% se diagnostica correctamente.

El objetivo es explorar patrones de síntomas, niveles de anticuerpos y diagnóstico según tipo de celiaquía.

## Dataset
Este conjunto de datos se tomó originalmente del Departamento de Biotecnología de la Universidad de Wageningen y Investigación de Alimentos en los Países Bajos. El dataset está disponible públicamente en [Kaggle](https://www.kaggle.com/datasets/andrewmvd/celiac-disease-patients).

Consisten en varias variables médicas como: edad, género, tipo de diabetes, sintomas(diarrea, hinchazon abdominal, heces pegajosas), tipo de estatura, perdida de peso, niveles de anticuerpos, tipo de lesiones intestinales, tipo de celiaquia y una variable objetivo que indica si el paciente es celíaco o no.

## Análisis Exploratorio de Datos (EDA)
El análisis incluye:
- Limpieza y preprocesamiento de datos
- Análisis estadístico descriptivo
- Visualización de distribuciones y correlaciones
- Identificación de patrones y tendencias
- Comparación entre diferentes tipos de celiaquía
- Análisis de síntomas más comunes y su relación con el diagnóstico
- Evaluación de niveles de anticuerpos en diferentes grupos de pacientes

## Herramientas Utilizadas
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebooks
- NumPy


## 🚀 Cómo reproducir el proyecto

1. Clonar el repositorio:

```bash
git clone url_del_repositorio
```
cd repositorio

2. Crear un entorno virtual (opcional pero recomendado):

```
python -m venv env
source env/bin/activate  # En Windows usa `env\Scripts\activate`
```

3. Instalar las dependencias:

```pip install -r requirements.txt
```

4. Abrir el notebook de Jupyter:

```jupyter notebook
```
5. Cargar el dataset y ejecutar las celdas del notebook para realizar el análisis.



# Notas

- El dataset original está en data/raw/..
- El dataset limpio se guarda en data/processed/.. después de la limpieza
- Se recomienda no sobrescribir los datos crudos.