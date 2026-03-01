# 🏋️‍♂️ Predicción de Retención y Segmentación de Usuarios
## 📝 Descripción del Proyecto
El objetivo principal de este proyecto es analizar los perfiles de los clientes de una cadena de gimnasios para predecir la probabilidad de cancelación (churn). A través de modelos de aprendizaje automático y técnicas de clustering, se identifican los factores clave que impulsan la lealtad y se proponen estrategias basadas en datos para reducir la deserción.

## 🎯 Objetivos
Análisis Exploratorio (EDA): Identificar las diferencias de comportamiento entre clientes que permanecen y los que se van.
Modelado Predictivo: Desarrollar y comparar modelos de clasificación para predecir la cancelación de usuarios.
Segmentación de Clientes: Agrupar a los usuarios mediante algoritmos no supervisados para personalizar las estrategias de retención.

## 🛠️ Tecnologías y Librerías
Python (versión 3.x)
Librerías principales: pandas y numpy para manipulación de datos.
Visualización: matplotlib y seaborn para gráficos estadísticos.
Machine Learning: scikit-learn para modelos de clasificación (LogisticRegression, RandomForestClassifier) y clustering (KMeans).

## 📊 Hallazgos Principales
Perfil del Desertor: 
Los usuarios que cancelan suelen tener contratos cortos (promedio de 1.7 meses) y una menor frecuencia de asistencia (1 vez por semana vs. 2 de los leales).
Importancia del Contrato: Existe una correlación negativa muy fuerte entre la duración del contrato y la cancelación; a mayor plazo, menor riesgo.
Eficacia del Modelo: La Regresión Logística alcanzó una precisión del 92.17% y una exhaustividad (recall) del 80.50%, superando ligeramente al Bosque Aleatorio en la identificación de desertores.

Segmentación por Riesgo:
Cluster 3: Grupo de riesgo crítico con un 57.29% de churn.
Cluster 2: Grupo de alta lealtad con contratos largos y solo un 2.20% de churn.

## ✅ Resultados y Conclusiones
Estrategia de Fidelización: Se recomienda incentivar la transición de contratos mensuales a planes de 6 o 12 meses, ya que la estabilidad del contrato es el predictor más fuerte.
Fase Crítica: La mayoría de las cancelaciones ocurren durante los primeros meses; es necesario un programa de "onboarding" intensivo durante los primeros 30-60 días.
Marketing Dirigido: Utilizar los clústeres identificados para enviar promociones de reactivación específicas a los Grupos 3, 4 y 0 antes de que completen su ciclo de abandono.
