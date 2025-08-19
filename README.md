# Desaf-o_Telecom_X_2

## 1. Objetivos del Proyecto 

Objetivo General: Desarrollar un modelo de machine learning para predecir la deserción de clientes (Churn) en una empresa de telecomunicaciones, con el fin de mejorar las estrategias de retención.

Objetivos Específicos:

Realizar una limpieza y un preprocesamiento exhaustivo de los datos para manejar valores nulos, convertir variables categóricas y estandarizar las numéricas.

Identificar y mitigar la multicolinealidad entre las variables predictoras para asegurar la estabilidad y la interpretabilidad de los modelos.

Ajustar el desbalance de clases en los datos de entrenamiento utilizando la técnica de submuestreo (undersampling) para evitar que los modelos se sesguen hacia la clase mayoritaria.

Construir y evaluar múltiples modelos de clasificación, incluyendo Random Forest, Regresión Logística, K-NN y XGBoost, para determinar cuál ofrece el mejor rendimiento en la predicción de la deserción.

Optimizar los hiperparámetros del modelo seleccionado para maximizar el recall y la precisión, identificando de manera efectiva a los clientes en riesgo de abandono.

## 2. Introducción
 
En el competitivo sector de las telecomunicaciones, la deserción de clientes (Churn) representa una pérdida significativa de ingresos y una amenaza para la estabilidad del negocio. Predecir con precisión qué clientes tienen probabilidades de abandonar el servicio es un desafío crítico que, de resolverse, permite a las empresas implementar estrategias de retención proactivas y personalizadas.

Este proyecto tiene como objetivo abordar este problema utilizando el aprendizaje automático. A través de un riguroso proceso que incluye la limpieza y el preprocesamiento de datos, la mitigación de la multicolinealidad y el manejo del desbalance de clases, buscando construir un modelo de predicción robusto y confiable. Se explorarán diversos algoritmos de clasificación, desde modelos lineales como la Regresión Logística hasta modelos de ensemble como Random Forest y XGBoost, para identificar el que mejor se adapte al conjunto de datos.

El análisis se centrará en el rendimiento de los modelos en la clase minoritaria (Churn = 1), utilizando métricas clave como el recall, la precisión y la matriz de confusión. Los hallazgos de este proyecto proporcionarán a la empresa una herramienta valiosa para identificar a los clientes en riesgo, optimizar sus esfuerzos de retención y fortalecer su posición en el mercado.

## 3. Conclusiones

Los resultados del análisis confirman que el modelo Random Forest fue el más adecuado para predecir la deserción de clientes, logrando un equilibrio favorable entre precisión y recall.

Rendimiento del Modelo: El modelo optimizado de Random Forest alcanzó una sensibilidad (recall) del 63% para la clase Churn. Esto significa que identificó correctamente a la mayoría de los clientes que realmente abandonaron el servicio, un logro crucial para el negocio.

Manejo de la Multicolinealidad: La reducción de variables como Charges.Total y la cuidadosa selección de otras características fue fundamental para eliminar la multicolinealidad perfecta y obtener un modelo estable.

Impacto del Submuestreo: La aplicación del submuestreo (undersampling) en el conjunto de entrenamiento fue vital para evitar que el modelo se sesgara. Aunque esto resultó en una precisión del 56% para la clase de abandono, el valor del recall demostró ser una contrapartida aceptable y valiosa.

En conclusión, el modelo desarrollado proporciona una base sólida para que la empresa de telecomunicaciones pueda tomar decisiones informadas sobre la retención de clientes. La capacidad de identificar a los clientes en riesgo de manera proactiva permitirá una asignación más eficiente de recursos y ayudará a reducir las tasas de deserción.
