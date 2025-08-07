---

## 🔍 Entrenamiento y Evaluación de Modelos de ML

Se abordó un problema de clasificación binaria: predecir si un videojuego tendría una **alta aprobación** (approval rate ≥ 75%).

Se probaron y compararon los siguientes modelos:
- Regresión Logística
- Random Forest

El modelo Random Forest fue seleccionado como final por su mayor rendimiento global.

| Modelo               | CV Accuracy (%) | Test Accuracy (%) |
|----------------------|------------------|-------------------|
| Regresión Logística  | 56.8 ± 0.38     | 57.6             |
| Random Forest        | 58.9 ± 0.52     | 57.8             |

---

## 🧪 Optimización de Hiperparámetros

Se utilizaron:
- `GridSearchCV` para Regresión Logística
- `RandomizedSearchCV` para Random Forest

El modelo final (Random Forest optimizado) logró:

- **CV Accuracy:** 61.4%
- **Test Accuracy:** 60.2%
- **Recall clase positiva (alta aprobación):** 43.5%

---

## 🧠 Interpretabilidad del Modelo

Se empleó SHAP para interpretar la contribución de cada variable a la predicción.

### Variables más influyentes (sin contar approval_rate):
1. Estimated Owners
2. Average Playtime
3. Price
4. Achievements
5. Game Age

Se incluyeron visualizaciones:
- Feature importance (%)
- SHAP beeswarm plot

---

## 💡 Insights y Recomendaciones

- Juegos con **alta aprobación previa** tienden a mantener buenas valoraciones.
- El **engagement** (tiempo de juego) y la **popularidad** (owners) son determinantes.
- El **precio competitivo** y los **logros** también tienen influencia.
- Se recomienda monitorear la aprobación temprana y ajustar experiencias iniciales.

---

## 📂 Recursos Finales

- 📘 Notebook Colab: [Colab](https://colab.research.google.com/drive/1J_EqnFxMxxayJKC3I8u4hLgmHQnVPsjW)
- 🗂️ Presentación Google Slides: [Slides](https://docs.google.com/presentation/d/1QhXNk24HiMCKhOEjJ8A-Nwfbx82DLKtQ6QaofZWveKQ)
- 💻 Repositorio GitHub: [GitHub Repo](https://github.com/LuckDwn/Data-Science-II-Luca-Montenegro)