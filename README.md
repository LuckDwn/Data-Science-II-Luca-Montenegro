# Data-Science-II-Luca-Montenegro
CODERHOUSE: Proyecto de Data Science II - Machine Learning para la Ciencia de Datos basado en datos de Steam / Luca Montenegro. Proyecto dedicado al análisis y modelado de ML para bases de datos de Steam. 


# 🎮 Machine Learning para la Ciencia de Datos | Proyecto Data Science II

Este repositorio contiene el desarrollo del proyecto final de **Data Science II**
---

## 🧠 Motivación

Steam es una de las plataformas de videojuegos más relevantes del mundo. Entender los factores que hacen exitoso a un juego puede aportar información clave para desarrolladores, publicadores y analistas de producto. Este proyecto busca descubrir patrones y variables relevantes que impactan en la valoración de un videojuego.

---

## 🎯 Objetivos

- 📂 **Importar y explorar datasets de Steam** desde Google Drive  
- 🔌 **Consultar la API oficial de Steam** para enriquecer los datos  
- 📊 **Identificar patrones y tendencias** mediante visualizaciones y estadísticas descriptivas  
- 🧠 **Proponer hipótesis de interés** y variables candidatas para el modelado  
- 📝 **Documentar insights relevantes** para la toma de decisiones ejecutivas  
- 🧼 **Limpieza y transformación profunda** de los datos (fechas, precios, outliers, escalado)  
- 🧱 **Ingeniería de atributos personalizada** (e.g. `approval_rate`, `game_age`, `estimated_owners`)  
- 🏷️ **Codificación de variables categóricas** como géneros y etiquetas (one-hot)  
- 📐 **Normalización de variables numéricas** para uso en modelos sensibles a escala  
- 🧪 **Entrenamiento de múltiples modelos de clasificación** (LogReg, RF, XGBoost)  
- 🧭 **Validación cruzada y selección de modelo óptimo**  
- 🛠️ **Optimización de hiperparámetros** para maximizar la performance  
- 🔍 **Interpretabilidad de modelos** mediante `feature_importance_` y SHAP  
- 💡 **Obtención de insights accionables** basados en el comportamiento de los datos  
- ✅ **Recomendaciones estratégicas concretas** para desarrolladores y publishers  
- 📽️ **Construcción de una presentación ejecutiva clara y visual**  
- 🗃️ **Publicación del proyecto completo** en GitHub y Google Slides

---

## 📁 Contenido del repositorio

- `Proyecto Final - Data Science II - Luca Montenegro.ipynb`: Notebook con el análisis completo
- `README.md`: Documentación del proyecto
- *(opcional)* `/imgs`: Carpeta con gráficos generados para la presentación

---
## 🖥️ Presentación ejecutiva

[🔗 Ver presentación en Google Slides](https://docs.google.com/presentation/d/1QhXNk24HiMCKhOEjJ8A-Nwfbx82DLKtQ6QaofZWveKQ/edit?usp=sharing)

## 📊 Datasets utilizados

Este análisis utiliza seis archivos CSV con información sobre más de 27,000 videojuegos en Steam:

| Archivo                        | Descripción                                      |
|-------------------------------|--------------------------------------------------|
| steam.csv                     | Dataset principal con ratings, precio, playtime |
| steam_description_data.csv    | Descripciones cortas y longitudes               |
| steam_support_info.csv        | Idiomas y modos de soporte                      |
| steamspy_tag_data.csv         | Etiquetas de juegos según SteamSpy              |
| steam_requirements_data.csv   | Requisitos mínimos del sistema                  |
| steam_media_data.csv          | Información multimedia                          |

> ⚠️ Nota: El dataset fue originalmente publicado en [Kaggle por el usuario hellknows](https://www.kaggle.com/datasets/hellknows/steam-games-dataset), pero actualmente fue retirado de la plataforma.
> Se encuentra disponible para su consulta en esta carpeta de Google Drive: 📂 🔗 [Ver carpeta de datasets en Google Drive
](https://drive.google.com/drive/folders/1zmmJIs9tPQDpLjCStiFRJ-rSAcXAyFrx?usp=drive_link)
---

## 🔗 Herramientas utilizadas

- Python 3 + Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- API pública de Steam
- GitHub para control de versiones
- Google Slides para presentación ejecutiva

---

## 📌 Estado del proyecto

✅ Análisis exploratorio completo  
🚧 Modelado predictivo pendiente (segunda entrega)  
🎯 Presentación ejecutiva disponible [aquí](https://docs.google.com/presentation/d/1QhXNk24HiMCKhOEjJ8A-Nwfbx82DLKtQ6QaofZWveKQ/edit?usp=sharing)

---

## 👨‍💻 Autor

Luca Montenegro  
Curso: Data Science II – Comisión 75690  

