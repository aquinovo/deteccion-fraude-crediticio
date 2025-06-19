# Implementación de Técnicas de Explicabilidad Basado en “One Explanation Does Not Fit All”

Este repositorio contiene el código, notebook y reporte asociados al análisis de explicabilidad local y global de un modelo de clasificación binaria para la detección de fraude en transacciones de tarjetas de crédito.

## Objetivo

Aplicar técnicas de explicabilidad local y global a un modelo de clasificación de fraude
crediticio.

## Estructura del repositorio

- [`Aquino Velasco Osorio.ipynb`](./Aquino%20Velasco%20Osorio.ipynb): Libreta Jupyter con todo el pipeline de análisis, entrenamiento, explicabilidad y visualización.
- [`Aquino Velasco Osorio.pdf`](./Aquino%20Velasco%20Osorio.pdf): Reporte formal en PDF con introducción, metodología, hallazgos, visualizaciones y conclusiones, referenciando el artículo "One Explanation Does Not Fit All".
- `creditcard.csv`: Base de datos utilizada (debe ser obtenida de [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)).
- `README.md`: Este archivo.

## Requisitos

- Python 3.12 o superior
- scikit-learn
- pandas
- matplotlib
- seaborn
- shap

Puedes instalar las dependencias con:

```bash
pip install scikit-learn pandas matplotlib seaborn shap
```

## Uso
1. Descarga la base de datos `creditcard.csv` desde Kaggle y colócala en el directorio raíz.
2. Abre y ejecuta [`Aquino Velasco Osorio.ipynb`](./Aquino%20Velasco%20Osorio.ipynb) para reproducir todo el flujo de análisis y explicabilidad.
3. Consulta [`Aquino Velasco Osorio.pdf`](./Aquino%20Velasco%20Osorio.pdf) para una explicación detallada del problema, metodología, resultados y recomendaciones.