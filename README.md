#Analiza danych z telefonów Samsung - Klasteryzacja i Klasyfikacja

##Wprowadzenie

Celem tego projektu jest analiza danych z telefonów Samsung dotyczących aktywności fizycznej użytkowników. W ramach zadania wykorzystano algorytmy klasteryzacji oraz klasyfikacji w celu podziału i identyfikacji różnych rodzajów aktywności. Projekt obejmuje analizę danych, dobór odpowiednich algorytmów,
ocenę jakości klasteryzacji oraz porównanie wyników klasyfikacji.

##Kroki realizacji:

1.Wczytanie i wstępna analiza danych

    Zbadanie potrzeby obróbki danych.

    Ocena istotności cech oraz struktury zbioru.

2.Zastosowanie metod klasteryzacji

    Skalowanie danych.

    Klasteryzacja przy użyciu metod: K-Means, DBSCAN, Gaussian Mixture Model (GMM).

    Dobór optymalnej liczby klastrów dla K-Means.

    Porównanie wyników z rzeczywistymi etykietami aktywności.

3.Wizualizacja wyników klasteryzacji

    Rysowanie wykresów klastrów dla poszczególnych algorytmów.

    Analiza rozmieszczenia punktów w klastrach.

4.Zastosowanie metod klasyfikacji

    Przeprowadzenie preprocessing danych.

    Wytrenowanie i ocena klasyfikatorów: Random Forest, SVM, KNN.

    Podział danych na zbiór treningowy i testowy (bez walidacji krzyżowej)

5.Analiza wyników i wnioski

    Ocena jakości klasteryzacji (ARI, NMI).

    Porównanie skuteczności klasyfikatorów.

    Odpowiedź na pytanie dotyczące różnic między K-Means, K-Fold i KNN.

##Funkcjonalności

1.Analiza danych wejściowych

    Wczytanie plików: samsung_train.txt, samsung_test.txt, samsung_train_labels.txt, samsung_test_labels.txt.

    Skalowanie danych.

    Analiza potrzeby redukcji wymiarowości.

2.Zastosowanie klasteryzacji

    Implementacja metod K-Means, DBSCAN, GMM.

    Wizualizacja wyników klasteryzacji.

    Analiza jakości podziału na klastry.

3.Optymalizacja liczby klastrów dla K-Means

    Wykorzystanie metody łokcia i silhouette score.

4.Ocena jakości klasteryzacji

    Metryki: ARI (Adjusted Rand Index), NMI (Normalized Mutual Information).

    Analiza rozrzutu aktywności w klastrach.

5.Zastosowanie metod klasyfikacji

    Trenowanie modeli Random Forest, SVM, KNN.

    Porównanie skuteczności modeli na zbiorze walidacyjnym i testowym.



