
# Trabajo Práctico 3: Aprendizaje No Supervisado

**Creado por:** Laura Cortés Hoyos

## 1. Descripción del dataset

Para el desarrollo de este trabajo se utilizó el dataset **Wine Quality**, que contiene información sobre las características fisicoquímicas de diferentes muestras de vino.

La base de datos inicial está conformada por 1.143 observaciones y 10 variables numéricas, entre ellas: acidez fija, acidez volátil, ácido cítrico, azúcar residual, cloruros, dióxido de azufre libre y total, densidad, pH y sulfatos.

Durante el proceso de limpieza se identificaron 127 registros duplicados, los cuales fueron eliminados, obteniendo una base de datos final de 1.016 observaciones.

## 2. Objetivo del trabajo

Aplicar técnicas de aprendizaje no supervisado para identificar patrones y agrupaciones dentro del conjunto de datos, utilizando el algoritmo K-means y el análisis de componentes principales (PCA).

Asimismo, comparar diferentes enfoques de agrupación mediante métricas como la inercia y el coeficiente Silhouette, con el propósito de identificar el modelo que presente una mejor separación de los grupos.

## 3. Principales hallazgos y conclusiones

- Se identificaron dos clusters con características fisicoquímicas diferentes.
- El modelo basado en PCA obtuvo el mejor desempeño, con un Silhouette Score de **0,3997**, superior al obtenido con las variables originales y seleccionadas.
- Las dos primeras componentes principales explicaron conjuntamente el **49,06 % de la variabilidad** de los datos.
- Se encontraron diferencias entre los grupos principalmente en variables como acidez fija, acidez volátil, ácido cítrico, cloruros y sulfatos.
- El primer cluster agrupó 689 observaciones (67,8 %), mientras que el segundo reunió 327 observaciones (32,2 %).

En conclusión, el enfoque PCA combinado con K-means permitió obtener la mejor agrupación entre los modelos evaluados. Los resultados demuestran que las técnicas de aprendizaje no supervisado son útiles para identificar patrones y segmentar observaciones según sus características fisicoquímicas. Sin embargo, la separación obtenida es moderada y los grupos identificados no representan directamente categorías de calidad del vino.
