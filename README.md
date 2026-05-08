# Bitcoin Market Analysis: Risk, Volatility & Predictive Modeling ₿📈

Este proyecto realiza un análisis cuantitativo profundo sobre el comportamiento histórico de Bitcoin, transformando datos crudos obtenidos mediante APIs en inteligencia financiera. El estudio se centra en la distribución de retornos, niveles de volatilidad y la aplicación de modelos predictivos avanzados.

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python.
* **APIs:** Extracción de datos financieros en tiempo real.
* **Análisis de Datos:** Pandas, NumPy.
* **Visualización Avanzada:** Matplotlib, Seaborn.
* **Machine Learning:** * Modelos: XGBoost, Random Forest, Linear Regression.
  * Técnicas: PCA (Principal Component Analysis), Cross-Validation, Hyperparameter Tuning.
  * Evaluación: MAE, RMSE, R².

## 📊 Metodología y Flujo Técnico
1. **Feature Engineering:** Creación de indicadores de volatilidad y dinámica de volumen.
2. **Reducción de Dimensionalidad (PCA):** Implementación de PCA para optimizar el espacio de características y analizar la varianza explicada.
3. **Modelado Predictivo:** Comparativa entre modelos lineales y de ensamble (Gradient Boosting).
4. **Validación:** Uso de validación cruzada para asegurar la estabilidad del modelo y análisis del compromiso Sesgo-Varianza.

## 📈 Conclusiones y Hallazgos Críticos
* **Dinámica de Mercado:** Se identificó que la volatilidad de Bitcoin presenta patrones de "cluster" donde movimientos extremos suelen preceder a periodos de alta inestabilidad.
* **Evaluación de Modelos:** Aunque modelos complejos como **XGBoost** mostraron estabilidad, el análisis reveló un escenario de *underfitting* debido a la naturaleza estocástica del precio, sugiriendo que la calidad de las variables es más determinante que la elección del algoritmo.
* **Análisis de PCA:** La reducción de dimensionalidad confirmó que las variables actuales capturan solo una fracción de la dinámica del activo, proponiendo la inclusión de indicadores macroeconómicos para futuras iteraciones.

---

*Ingeniero Mecánico | Data Science & Analytics* [LinkedIn](https://www.linkedin.com/in/santiago-alonso-hinojo/) | [GitHub](https://github.com/SantiagoAlonsoW)
