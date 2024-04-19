Der Datensatz stammt aus der WHO-Datenbank und beeinhaltet Daten zu der durchschnittliche Lebenserwartung globaler Länder zwischen den Jahren 2000 und 2015.
Der Datensatz besitzt einen höhen Anteil von fehlenden Daten zum Typ MCAR (Missing-Completely-at-Random) und einen kleinen Anteil zum Typ MAR (Missing-at-random).

Aus Literaturrecherche werden in dieser Seminararbeit 9 Verfahren bestimmt, die fehlenden Daten zum Typ MCAR und MAR in einem multivariaten Datensatz gut ersetzen können.
DArunter sind 4 statistoische Ersatzverfahren, 4 Machine Learning Verfahren und 1 Deep Learning Verfahren
Diese sind nämlich - 1.Forward-Imputation, 2. Backward-Imputation, 3.Mean-Imputation, 4. Median-Imputation 5.KNN-Verfahren, 6.MICE-Imputation, 7. MissForest-Imputation mit SVM als Klassfizierer, 8. Expectation-Maximization Algorithmus, 9. LSTM-Verfahren

In diesem Notebook werden diese Imputationsalgorithmen auf den Datensatz angewandt und deren Evaluationsergebnisse miteinander vergleichen, um die besten Imputationsalgorithmen zu bestimmen.
