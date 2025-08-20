# challenge-data-science_TelecomX_parte2
# 📊 Informe de Conclusión – Análisis de Cancelación de Clientes (Churn)

## 1. Objetivo del Estudio
El análisis tuvo como propósito identificar los factores que influyen en la cancelación de clientes y evaluar modelos predictivos capaces de anticipar este comportamiento. A partir de los resultados, se buscó proponer estrategias de retención basadas en datos.

---

## 2. Resultados de los Modelos

- **Regresión Logística**  
  - Mostró buen rendimiento en exactitud y recall.  
  - Su ventaja principal es la interpretabilidad de los coeficientes.  
  - Requirió normalización de las variables para un mejor ajuste.

- **Random Forest**  
  - Obtuvo el mejor desempeño general en métricas como F1-score.  
  - Captura relaciones no lineales y maneja mejor la complejidad de los datos.  
  - Permite analizar la importancia de cada variable de forma clara.

En conclusión, el modelo de **Random Forest** fue el más sólido en predicciones, mientras que la Regresión Logística aportó interpretabilidad.

---

## 3. Factores que más influyen en la cancelación

De acuerdo con la importancia de variables y coeficientes:

- **Tiempo de permanencia (tenure):** clientes con poca antigüedad presentan mayor tendencia a cancelar.  
- **Cargos totales y mensuales:** valores elevados incrementan la probabilidad de churn.  
- **Servicios adicionales (soporte técnico, seguridad, respaldos):** la ausencia de estos servicios aumenta la tasa de cancelación.  
- **Características demográficas (ej. seniorcitizen):** tienen cierta influencia, pero menor en comparación con las variables financieras y de permanencia.

---

## 4. Observaciones sobre los Modelos
- **Overfitting:** no se detectó un sobreajuste fuerte en Random Forest, aunque la diferencia entre entrenamiento y prueba debe seguir monitoreándose.  
- **Underfitting:** la Regresión Logística puede simplificar demasiado el problema, captando menos interacciones complejas entre variables.

---

## 5. Estrategias de Retención
A partir de los hallazgos, se recomiendan las siguientes acciones:

1. **Fidelización temprana:** ofrecer incentivos a clientes nuevos para alargar su permanencia.  
2. **Planes adaptados a precios:** personalizar tarifas para clientes sensibles a costos altos.  
3. **Servicios de valor agregado:** incentivar el uso de soporte técnico, seguridad online y respaldos.  
4. **Segmentación de clientes en riesgo:** aplicar estrategias proactivas de retención en perfiles con mayor propensión a cancelar.

---

## 6. Conclusión General
El análisis confirmó que los factores más relevantes para la cancelación de clientes son la **antigüedad en el servicio** y los **cargos mensuales/totales**.  
El modelo de **Random Forest** se posicionó como el más robusto para predecir la cancelación, mientras que la **Regresión Logística** fue útil para interpretar el peso de cada variable.  
Los resultados permiten diseñar estrategias concretas de retención, reduciendo el churn y mejorando la relación a largo plazo con los clientes.
