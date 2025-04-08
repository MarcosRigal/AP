<div align="center">
    <img width="100%" src="https://www.initiumsoft.com/blog_initium/wp-content/uploads/2024/08/deep-learning.webp" alt="FOTO">
</div>

# Adapting Performance Metrics for Ordinal Classification to Interval Scale

Este repositorio contiene el trabajo realizado para el Máster Universitario en Inteligencia Computacional e Internet de las Cosas de la Universidad de Córdoba, en el marco de la asignatura de Aprendizaje Profundo.

## 📘 Descripción

El trabajo es una sintesis del articulo Binotto et all que propone una adaptación de métricas clásicas de clasificación ordinal (como MAE y TC) para escenarios donde las clases representan **intervalos numéricos desiguales**. La idea central es que **la magnitud real del error importa** más allá de la posición ordinal.

Entre los aspectos clave se encuentran:

- Sustitución de la diferencia de índices ordinales por distancias reales entre intervalos.
- Uso de densidades de clase en lugar de conteos absolutos.
- Normalización de métricas adaptadas al rango [0, 1].
- Tratamiento especial para clases con intervalos abiertos.

## 📂 Estructura del Repositorio

```
├── metricas_ordinales_vs_adaptadas.ipynb   # Cuaderno Jupyter con experimentos y análisis
├── i92rigam-slides.pdf                     # Presentación de diapositivas
├── i92rigam-doc.pdf            			# Memoria escrita (formato Springer LNCS)
```