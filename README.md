# 🎬 Análisis de Sentimiento - Film Junky Union

## 📝 Caso de Negocio
La comunidad **Film Junky Union** necesitaba un sistema automatizado para filtrar y clasificar las reseñas de películas. El objetivo principal fue entrenar un modelo que detecte críticas negativas automáticamente para moderación de contenido.

## 🛠️ Metodología Técnica
- **Preprocesamiento de Texto:** Limpieza de datos, eliminación de stopwords y normalización de texto para reducir el ruido.
- **Vectorización:** Implementación de **TF-IDF** (Term Frequency-Inverse Document Frequency) para convertir texto en representaciones numéricas que los modelos puedan entender.
- **Modelado:** Se compararon varios modelos (Regresión Logística, LightGBM), seleccionando el más eficiente en términos de velocidad y precisión.
- **Métrica Clave:** Se superó el umbral de **0.85 en el F1-Score**, garantizando un equilibrio óptimo entre precisión y sensibilidad (Recall).

## 📊 Resultados
El sistema es capaz de clasificar reseñas con alta fidelidad, permitiendo a la plataforma automatizar gran parte de su proceso de moderación y entender mejor la opinión de su comunidad.

## 🧰 Stack Técnico
`Python`, `NLTK`, `Scikit-Learn`, `TF-IDF`, `Logistic Regression`.
