# CallengeTelecom2
Modelos predictivos del análisis de ventas

Informe de Análisis de Cancelación de Clientes (Churn) – Telecom X
1. Objetivo del análisis

El objetivo de este proyecto fue analizar los factores que influyen en la cancelación de clientes (churn) en la empresa Telecom X utilizando técnicas de análisis de datos y modelos de machine learning. A través de este análisis se busca identificar patrones que permitan anticipar la cancelación de clientes y proponer estrategias de retención.

2. Análisis exploratorio de datos

Durante el análisis exploratorio se observó que existe un desbalance entre clientes que permanecen y clientes que cancelan el servicio, lo cual es importante considerar al construir modelos predictivos.

El análisis de correlación permitió identificar algunas variables con mayor relación con la cancelación. Entre las variables con mayor correlación positiva con churn se encuentran:

InternetService_Fiber optic

PaymentMethod_Electronic check

Charges_Monthly

PaperlessBilling_Yes

SeniorCitizen

Por otro lado, variables como tenure y Contract_Two year mostraron correlaciones negativas, lo que indica que los clientes con mayor tiempo en la empresa o contratos más largos tienden a cancelar menos.

3. Modelos predictivos

Se desarrollaron dos modelos de machine learning para predecir la cancelación de clientes:

Regresión Logística
Este modelo permitió analizar la influencia de cada variable mediante sus coeficientes y requiere normalización de datos.

Árbol de Decisión
Este modelo permite identificar patrones y reglas de decisión en los datos sin necesidad de normalización.

Ambos modelos fueron evaluados utilizando métricas como:

Accuracy

Precision

Recall

F1-score

Matriz de confusión

4. Variables más influyentes

El análisis de los coeficientes del modelo de Regresión Logística permitió identificar las variables que tienen mayor impacto en la probabilidad de cancelación.

Las variables más relevantes fueron:

Charges_Total

InternetService_Fiber optic

PaymentMethod_Electronic check

StreamingTV_Yes

MultipleLines_Yes

PaperlessBilling_Yes

Estos resultados indican que el tipo de servicio contratado, el método de pago y el comportamiento de consumo del cliente influyen significativamente en la cancelación.

5. Factores principales de cancelación

A partir del análisis realizado se identificaron los siguientes factores clave que afectan la cancelación:

Clientes con contratos mensuales presentan mayor probabilidad de churn.

Los clientes con menor tiempo de permanencia (tenure) cancelan con mayor frecuencia.

El método de pago Electronic check está asociado con mayores tasas de cancelación.

Los clientes con servicio de fibra óptica muestran una mayor tendencia a cancelar el servicio.

6. Estrategias de retención

Con base en los resultados del análisis, se proponen las siguientes estrategias para reducir la cancelación de clientes:

Incentivar contratos de mayor duración mediante descuentos o beneficios.

Implementar programas de fidelización para clientes nuevos durante los primeros meses de servicio.

Analizar la satisfacción de los clientes con servicio de fibra óptica para mejorar la calidad del servicio.

Promover métodos de pago automáticos que están asociados con menor cancelación.

Utilizar modelos predictivos para identificar clientes con alto riesgo de churn y ofrecerles promociones personalizadas.

7. Conclusión

El análisis permitió identificar variables clave que influyen en la cancelación de clientes. Los modelos de machine learning desarrollados permiten predecir el churn con un nivel aceptable de precisión y pueden servir como herramienta para apoyar estrategias de retención.

Aplicar estrategias basadas en estos resultados puede ayudar a Telecom X a mejorar la fidelización de clientes y reducir la tasa de cancelación.
