# 📊 Modelo Predictivo para la Identificación de Pólizas no Renovadas

## 📌 Descripción
Proyecto académico orientado al procesamiento y análisis de datos del sector asegurador para preparar la información utilizada en un modelo predictivo de renovación de pólizas.

## 👥 Integrantes
- Juan Carlos Fonseca Florez
- Zarith Dorelly Gómez Vargas
- Erika Fernanda Jiménez Camargo

## 🛠️ Tecnologías
- Python
- Pandas y NumPy
- Matplotlib y Seaborn
- Scikit-learn

## 📁 Archivos de entrada
- `Datos_Preprocesamiento.csv`: datos principales de las pólizas.
- `serie_Historica.xlsx`: información histórica del riesgo país.
- `inflacion_variacion_anual_ipc_chile.xlsx`: datos históricos de inflación.

## ⚙️ Proceso
1. Exploración y limpieza de datos.
2. Tratamiento de valores nulos y duplicados.
3. Incorporación de variables económicas: riesgo país e inflación.
4. Creación de la variable `Dias_Entre_Aviso_Cierre`.
5. Análisis de correlaciones y de la variable objetivo `NO_Renovada`.
6. Exportación del conjunto procesado como `Datos_Final.csv`.

## 🚀 Instalación

Instalar las dependencias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

Abrir el notebook en Jupyter Notebook o Google Colab y ejecutar las celdas en orden, verificando que los archivos de entrada estén disponibles.

## 📌 Resultado
Se obtiene un conjunto de datos procesado y enriquecido para las siguientes etapas del proyecto predictivo.

**Proyecto desarrollado con fines académicos.**
