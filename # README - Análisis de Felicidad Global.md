# README - Análisis de Felicidad Global

# Análisis de Felicidad Global

---

## Tabla de Contenidos

1. [Introducción](#introducción)
2. [Declaración del Problema](#declaracion-del-problema)
3. [Recolección de Datos](#recolección-de-datos)
4. [Limpieza y Preparación de Datos](#limpieza-y-preparación-de-datos)
5. [Análisis Exploratorio de Datos (EDA)](#análisis-exploratorio-de-datos-eda)
6. [Ingeniería de Características](#ingeniería-de-características)
7. [Construcción y Evaluación de Modelos](#construcción-y-evaluación-de-modelos)
8. [Visualizaciones y Pronósticos](#visualizaciones-y-pronósticos)
9. [Resultados y Discusión](#resultados-y-discusión)
10. [Conclusión](#conclusión)
11. [Trabajo Futuro](#trabajo-futuro)
12. [Instalación](#instalación)
13. [Uso](#uso)
14. [Contribuciones](#contribuciones)


---

## Introducción
Este proyecto tiene como objetivo analizar factores socioeconómicos que afectan la percepción de felicidad a nivel global, utilizando datos del **World Happiness Report**. El análisis incluye tendencias históricas, identificación de variables clave y predicción de niveles futuros de felicidad en países seleccionados.

---

## Declaración del Problema
- Objetivo principal: Entender qué factores influyen más en los puntajes de felicidad.
- Objetivos específicos:
    - Analizar tendencias globales de felicidad.
    - Identificar variables socioeconómicas clave.
    - Predecir niveles futuros usando modelos supervisados.

---

## Recolección de Datos
- Fuente: Dataset World Happiness Report.
- Variables principales:
    - Life Ladder (Escalera de Vida).
    - PIB per cápita.
    - Apoyo social.
    - Expectativa de vida saludable.

---

## Limpieza y Preparación de Datos
- Identificación de valores nulos y tratamiento con interpolación.
- Eliminación de outliers usando métodos estadísticos.
- Normalización y transformación de variables.

---

## Análisis Exploratorio de Datos (EDA)
- Mapas de calor para identificar correlaciones.
- Gráficos de distribución de datos.
- Tendencias históricas por regiones.
Ejemplo: Alta correlación entre PIB per cápita y Life Ladder.

---

## Ingeniería de Características
- Reducción de dimensionalidad usando PCA (Análisis de Componentes Principales).
- Creación de nuevas características basadas en tendencias temporales.

---

## Construcción y Evaluación de Modelos
Se implementaron varios modelos predictivos:
    1. Regresión Lineal: Modelo base, limitado para datos no lineales.
    2. Random Forest: Mejor desempeño en términos de precisión y generalización.
    3. KNN y SVM: Capturan relaciones locales y no lineales.
    4. ARIMA: Análisis de series temporales para proyecciones futuras.
Métricas utilizadas:
- Error cuadrático medio (MSE).
- Coeficiente R².

---

## Visualización y Pronósticos
- Comparación de puntajes reales vs predichos.
- Predicciones de felicidad para 2025 en países seleccionados (España, Brasil, Venezuela).
- Gráficos de tendencias temporales.

---

## Resultados y Discusión
- Random Forest fue el modelo más preciso, superando a la regresión lineal y otros enfoques.
- Variables clave: PIB per cápita, apoyo social y expectativa de vida saludable.
- Predicciones: Estabilidad general, con mayor variabilidad en países en desarrollo.

---

## Conclusión
- Principales hallazgos:
    - Factores económicos y sociales influyen directamente en la felicidad.
    - Diferencias significativas entre regiones desarrolladas y en desarrollo.
- Aplicabilidad:
    - Información relevante para formulación de políticas públicas y toma de decisiones estratégicas.

---

## Trabajo Futuro
- Incorporar variables adicionales (educación, contaminación).
- Explorar el uso de redes neuronales para mejorar las predicciones.
- Realizar análisis a nivel regional más detallado.

---

## Instalación
    1. Clonar el repositorio:
        git clone https://github.com/usuario/proyecto-felicidad.git
        cd proyecto-felicidad
    2. Instalar dependencias:
        pip install -r requirements.txt
        
---

## Uso
    Ejecuta el notebook principal para reproducir el análisis:
        jupyter notebook Nueva\ Versión_Dec17.ipynb

---

## Contribuciones
Contribuciones son bienvenidas. Para colaborar:

Realiza un fork del repositorio.
Crea una nueva rama: git checkout -b nueva-funcionalidad.
Realiza los cambios y crea un pull request.

---