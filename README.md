# 📱 Análisis Predictivo de Adicción al Celular en Adolescentes

## Descripción

Proyecto de análisis de datos sobre el uso del celular en adolescentes, orientado a comprender cómo el uso excesivo del dispositivo se relaciona con variables emocionales, conductuales y académicas. Incluye un análisis exploratorio completo y modelos de machine learning para predecir el nivel de adicción.

Desarrollado en Python con Google Colab.

## Objetivos

- Identificar patrones de uso del celular en adolescentes.
- Explorar correlaciones entre el uso del dispositivo y variables como ansiedad, depresión, autoestima y rendimiento académico.
- Construir modelos predictivos para estimar el nivel de adicción.

## Dataset

Dataset estructurado con variables conductuales, emocionales y académicas de adolescentes. Incluye tanto variables categóricas como numéricas.

## Metodología

1. **Limpieza y preparación de datos**: tratamiento de valores nulos y revisión de tipos de variables.
2. **Análisis exploratorio (EDA)**: visualizaciones univariadas, bivariadas y multivariadas para identificar patrones y correlaciones.
3. **Modelado predictivo**: entrenamiento de modelos de regresión (Random Forest, LightGBM, Linear Regression).
4. **Evaluación**: métricas R² y MSE; análisis de feature importances para interpretar los factores más relevantes.

## Resultados principales

- Se identificaron los factores conductuales y emocionales con mayor correlación al nivel de adicción.
- Los modelos alcanzan un R² moderado, con margen de mejora mediante feature engineering.
- Las visualizaciones exponen relaciones claras entre el tiempo de pantalla y variables como ansiedad y rendimiento académico.

## Tecnologías utilizadas

| Herramienta | Uso |
|---|---|
| Python 3.x | Lenguaje principal |
| pandas / numpy | Manipulación de datos |
| matplotlib / seaborn | Visualización |
| scikit-learn | Modelado y métricas |
| LightGBM | Modelo de gradient boosting |
| Google Colab | Entorno de desarrollo |

## Cómo ejecutar el proyecto

1. Clonar el repositorio:
```bash
   git clone https://github.com/pragamarcos/data-science-proyecto-adiccion.git
```
2. Abrir `ProyectoDS_Praga.ipynb` en Google Colab o Jupyter Notebook.
3. Ejecutar las celdas en orden para replicar el análisis completo.

## Próximos pasos

- Ajuste de hiperparámetros con GridSearchCV / Optuna.
- Creación de nuevas variables derivadas (feature engineering).
- Mejorar la interpretabilidad con SHAP values.

## Contacto

[LinkedIn](https://www.linkedin.com/in/marcospraga/) · [GitHub](https://github.com/pragamarcos)
