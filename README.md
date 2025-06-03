Predicción de Cáncer de Pulmón a partir de Datos Tabulares utilizando Modelos de Machine Learning

Este repositorio contiene el Trabajo Final de Máster (TFM) de Pedro Ojeda Soto, desarrollado en el marco del Máster en Bioinformática y Bioestadística de la Universitat Oberta de Catalunya (UOC).

Descripción del proyecto

El objetivo principal de este proyecto es implementar y comparar tres modelos de Machine Learning ,Regresión Logística, Random Forest y XGBoost para predecir el diagnóstico de cáncer de pulmón a partir de un conjunto de datos clínicos, demográficos y conductuales.

El conjunto de datos utilizado fue obtenido desde la plataforma pública [Kaggle](https://www.kaggle.com/datasets/suryansh22/lung-cancer-dataset), en el proyecto titulado “Survey Lung Cancer”, publicado por el usuario Suryansh Tyagi. El archivo original, denominado `survey lung cancer.csv`, contiene 309 registros y 16 variables.

La detección temprana del cáncer de pulmón es clave para mejorar la supervivencia y el acceso a tratamientos eficaces. Mediante el uso de modelos de clasificación supervisada aplicados a datos tabulares, este trabajo busca contribuir al desarrollo de herramientas predictivas que apoyen la toma de decisiones clínicas de forma interpretable y reproducible.

Estructura del Script Principal

El archivo Script_TFM.Rmd contiene todo el flujo de trabajo necesario para reproducir el análisis. A continuación se describen sus principales secciones:

1. Carga de datos y preprocesamientos
2. Visualización exploratoria
3.Box-plot Genero/Edad vs Cancer de Pulmón
4. Modelos Regresión Logística, Random Forest y XGboost con validación cruzada y Umsampling
5. Modelos Regresión Logística con validación cruzada y Umsampling
6. Modelo Random Forest con validación cruzada y Umsampling
7. Modelo XGboost con validación cruzada y Umsampling
8. Intervalos de Confianza para las Métricas
9. Importancia de Variables para Modelo Logístico
10.Importancia de Variables para Random Forest
11.Importancia de Variables para XgBoost
12.Matriz de confusión para Regresión Logística
13.Matriz de confusión para Random Forest
14.Matriz de confusión para XgBoost
15.Intervalo de Confianza para las Métricas

Cómo comenzar.

Opción 1: Clonar el repositorio desde la terminal o consola de R

Si usas terminal o estás trabajando desde R/RStudio, puedes clonar este repositorio con:

```bash
git clone https://github.com/pojedaso/TFM_2025.git
cd TFM_2025
```

Desde R también puedes ejecutar:

```r
system("git clone https://github.com/pojedaso/TFM_2025.git")
setwd("TFM_2025")
file.edit("Script_TFM.Rmd")
```

Esto descargará el repositorio y abrirá el script principal para que puedas comenzar el análisis.

Opción 2: Usar RStudio con Git (recomendado para reproducibilidad)

1. Abre RStudio.
2. Ve a: **File > New Project > Version Control > Git**.
3. En el campo **Repository URL**, escribe:

   ```
   https://github.com/pojedaso/TFM_2025.git
   ```

4. Selecciona una carpeta local donde se descargará el repositorio.
5. Haz clic en **Create Project**.
6. Abre el archivo `Script_TFM.Rmd` para comenzar el análisis.


