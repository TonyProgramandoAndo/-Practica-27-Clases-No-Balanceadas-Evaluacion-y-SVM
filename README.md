Carga y exploración del dataset

Utiliza el dataset breast_cancer

Verifica la distribución de clases.

Visualiza con un gráfico la distribución y las principales características.

Entrenamiento base con SVM

Usa un modelo SVM con kernel RBF.

Aplica StratifiedKFold con 5 particiones.

Evalúa con métricas por clase: precisión, recall, F1-score.

Calcula y reporta métricas promedio y por clase.

Análisis del problema de desbalance

Interpreta las métricas: ¿qué clase tiene peor desempeño? ¿por qué?

Reporta matriz de confusión promedio.

Aplicación de SMOTE

Aplica SMOTE solo al conjunto de entrenamiento dentro de cada fold.

Entrena nuevamente la SVM.

Compara métricas antes y después.

Visualización y conclusiones

Usa un gráfico de barras comparando F1 por clase antes y después.

Comenta las ventajas y riesgos de aplicar SMOTE con SVM.

Explica cuándo conviene usar otras técnicas como One-Sided Selection o ADASYN.
