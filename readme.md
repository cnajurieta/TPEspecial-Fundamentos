# Trabajo Práctico Especial: Fundamentos de la Ciencia de Datos 2026

## Análisis del conjunto de datos CKD-NHANES 2021-2023

**Materia:** Fundamentos de la Ciencia de Datos 2026  
**Alumnos/Grupo:** 
Grupo 9 
- Campo Zambotti, Agustin.
- Najurieta, Constanza Belén
- Rosani, Nicolas Javier.

---

## Descripción del Proyecto

Este repositorio contiene el trabajo práctico especial cuyo objetivo es realizar un análisis exploratorio y estadístico del conjunto de datos **CKD-NHANES 2021-2023**. El estudio se centra en la enfermedad renal crónica (CKD) utilizando datos demográficos, medidas corporales, análisis de sangre/orina y antecedentes médicos de las personas registradas.

A lo largo de este análisis se abordan tareas de limpieza de datos, exploración inicial y planteo/validación de las hipótesis planteadas tanto como por el grupo como por la catedra.

---

## Requisitos para ejecutar este proyecto

Para ejecutar el código de este análisis, el entorno debe contar con:

*   **Python 3.8** o superior.
*   **Jupyter Notebook** o **JupyterLab** (para visualizar e interactuar con el análisis).
*   Gestor de paquetes `pip`.

---

## Paso a paso

Para preparar el entorno y ejecutar el trabajo práctico localmente siga los siguientes pasos:

### Paso 1: Clonar o descargar el repositorio
Clonar el repositorio de git con el siguiente link: 
```bash
git clone https://github.com/cnajurieta/TPEspecial-Fundamentos.git
cd Practica especial
```

### Paso 2: Crear un entorno virtual

**En Windows:**
```cmd
python -m venv venv
.\venv\Scripts\activate
```

**En Linux / macOS:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### Paso 3: Instalar las dependencias
Con el entorno virtual activado, instale las librerías necesarias (Pandas, Matplotlib, Seaborn, etc.) ejecutando el siguiente comando:

```bash
pip install -r requirements.txt
```

### Paso 4: Ejecutar el análisis
Una vez instaladas las dependencias, inicie Jupyter Notebook ejecutando:

1. Navegue en la interfaz de Jupyter hasta el archivo principal del análisis (por ejemplo: `TP_Especial_CKD.ipynb`).
2. Abra el archivo.
3. Para ejecutar todo el análisis de principio a fin, vaya al menú superior y seleccione **Kernel > Restart & Run All** (o "Reiniciar y ejecutar todo").

---

## Estructura del Repositorio

Para facilitar la corrección, el proyecto está organizado de la siguiente manera:

```text
├── .gitignore
├── CKD_NHANES_2021_2023.csv  # Dataset original del estudio
├── README.md                 # Archivo con la documentación del proyecto
├── requirements.txt          # Dependencias necesarias (pandas, numpy, seaborn, etc.)
├── TP_Especial_CKD_NHANES.ipynb # Notebook principal con el análisis exploratorio y de hipótesis
```

---
