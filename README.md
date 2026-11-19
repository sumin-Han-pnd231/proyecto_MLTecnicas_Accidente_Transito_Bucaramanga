# proyecto_MLTecnicas_Accidente_Transito_Bucaramanga

# Análisis y Modelado Predictivo de Accidentes de Tránsito en Bucaramanga (2012–2023)

Proyecto de **Técnicas de Aprendizaje de Máquina** enfocado en analizar la siniestralidad vial del municipio de Bucaramanga, Colombia, mediante técnicas de análisis exploratorio y modelado supervisado.

**Autores:** Tomas Charria · Emilio Gómez · Sumin Han · Juan David Nieto

---

## Propósito y Objetivos

El proyecto busca comprender los patrones detrás de los **39,193 accidentes de tránsito** registrados entre 2012 y 2023 y construir modelos capaces de apoyar la toma de decisiones en seguridad vial a través de tres frentes principales:

1. **Análisis Exploratorio y Estadístico (EDA):**
   * Evaluar tendencias temporales (anuales, mensuales y por franja horaria) y distribución geográfica por comunas y barrios.
   * Analizar la relación estadística entre la severidad de los siniestros y factores como la jornada (*diurna/nocturna*), el tipo de propietario (*particular/empresa*), los actores viales involucrados (motos, automóviles, peatones, etc.) y el número de vehículos.

2. **Clasificación de Gravedad:**
   * Desarrollar y comparar distintos algoritmos de clasificación (*Regresión Logística, Árboles de Decisión, SVM y Gradient Boosted Trees*) para predecir la gravedad de un accidente en tres categorías: **Solo daños**, **Con heridos** o **Con muertos**, aplicando técnicas de balanceo de clases (SMOTE).

3. **Predicción de Frecuencia:**
   * Modelar y estimar el conteo de accidentes según combinaciones de fecha, comuna y franja horaria mediante enfoques de regresión (*Regresión Lineal* y *Random Forest Regressor*).
