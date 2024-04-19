Der Datensatz stammt aus der WHO-Datenbank und beeinhaltet Daten zu der durchschnittliche Lebenserwartung globaler Länder zwischen den Jahren 2000 und 2015.
Der Datensatz besitzt einen höhen Anteil von fehlenden Daten zum Typ MCAR (Missing-Completely-at-Random) und einen kleinen Anteil zum Typ MAR (Missing-at-random).

Aus Literaturrecherche wird in dieser Seminararbeit 9 Verfahren bestimmt, die fehlenden Daten zum Typ 'MCAR' und 'MAR' in einem multivariaten, zeitbasierten Datensatz gut ersetzen können.
Darunter sind 4 statistische Ersatzverfahren, 4 Machine Learning Verfahren und 1 Deep Learning Verfahren.
Diese sind nämlich - 1.Forward-Imputation, 2. Backward-Imputation, 3.Mean-Imputation, 4. Median-Imputation, 5.KNN-Imputation, 6.MICE-Imputation, 7. MissForest-Imputation mit SVM als Klassfizierer, 8. Expectation-Maximization Algorithmus, und 9. LSTM-Verfahren

In diesem Notebook werden diese Imputationsalgorithmen auf den Datensatz angewandt und deren Evaluationsergebnisse miteinander vergleichen, um die besten Imputationsalgorithmen zu bestimmen.
