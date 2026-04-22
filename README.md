Este proyecto consiste en el desarrollo de un pipeline de aprendizaje supervisado para la predicción de una variable binaria (target) a partir de un dataset desbalanceado.

Se realiza una separación estratificada de los datos en conjuntos de desarrollo y evaluación, seguida del entrenamiento de un árbol de decisión y su evaluación mediante validación cruzada (K-Fold) utilizando métricas adecuadas para clases desbalanceadas como Accuracy, AUPRC y AUROC.

Posteriormente, se comparan distintos modelos de machine learning, incluyendo Decision Trees, KNN, SVM, LDA y Naive Bayes, junto con la optimización de hiperparámetros mediante búsqueda aleatoria y grillas manuales.

Finalmente, se analiza el desempeño de cada modelo considerando tanto su capacidad predictiva como su generalización, concluyendo que KNN presenta el mejor equilibrio entre rendimiento y sobreajuste.
