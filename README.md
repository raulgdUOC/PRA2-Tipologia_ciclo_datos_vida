# PRA2 ¿Cómo realizar la limpieza y análisis de datos?
# Autores
- Juan Luis Andión Tápiz | mail: [jandion@uoc.edu](jandion@uoc.edu)
- Raúl García Díaz | mail: [raulgd@uoc.edu](raulgd@uoc.edu)

## Descripción
Asignatura: M2.851 / Fecha 16-06-2023

URL de la base de datos elegida: https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

## Descripción del repositorio:

- `memoria.pdf`: Documento con una descripción más detallada del proyecto.
    - `/src/heart_notebook.ipynb`: Archivo que contiene el código que ha hecho falta para realizar la práctica.
    - `/src/requirements.txt`: Lista de paquetes utilizados (python 3.10).
    - `/data/heart.csv`: Dataset extraído de la URL mencionada anteriormente.
    
## Estructura del dataset

La información del dataset es la siguiente:

- `age`: Edad del paciente (0: Mujer. 1: Hombre).
- `cp` : Tipo de dolor en el pecho:
    - `0`: Asintomático.
    - `1`: Angina típica.
    - `2`: Angina no típica.
    - `3`: Dolor no relacionado con la angina.
- `trestbps`: Presión arterial en reposo (en mm Hg al ingreso al hospital).
- `chol`: Colesterol en suero en mg/dL.
- `fbs`: Nivel de azúcar en sangre en ayunas > 120 mg/dL (1 = True; 0 = False).
- `thalach`: Máximas pulsaciones registradas.
- `exang`: Angina inducida por ejercicio (1 = yes; 0 = no).
- `oldpeak`: Depresión del segmento ST inducida por ejercicio en relación al reposo.
- `slope`: La pendiente del segmento ST en el pico del ejercicio (2 = ascendente; 1 = plano; 0 = descendente).
- `caa`: Número de vasos principales (0-3) coloreados por fluoroscopia.
- `thal`: Talasemia (2 = normal; 1 = defecto fijo; 3 = defecto reversible).
- `output`: Diagnóstico de enfermedad cardíaca (estado de enfermedad angiografía)
    - `0`: Menos probabilidad de un ataque al corazón.
    - `1`: Mas probabilidad de un ataque al corazón.

