# Analiza MFPT z Resetowaniem Stochastycznym (Stochastic Resetting)

Projekt analizuje zjawisko stochastycznego resetowania w jednowymiarowym procesie dyfuzji. Celem jest zbadanie Średniego Czasu Pierwszego Przejścia (MFPT - Mean First Passage Time) do celu oraz znalezienie optymalnego wskaźnika resetowania ($\lambda^*$), który ten czas minimalizuje. 

## Główne Funkcjonalności:
* **Analiza teoretyczna:** Obliczanie dokładnych wartości MFPT na podstawie wzoru analitycznego oraz wyznaczanie teoretycznego optimum za pomocą biblioteki `scipy.optimize`.
* **Symulacje Monte Carlo:** Szybka implementacja numeryczna błądzenia losowego (Random Walk) z resetowaniem, zoptymalizowana przy użyciu kompilatora JIT (biblioteka `numba`).
* **Weryfikacja wyników (Backtesting):** Obliczanie błędów dopasowania symulacji do teorii za pomocą wskaźników **MAPE** (Mean Absolute Percentage Error) oraz **RMSE**.
* **Wizualizacja:** Generowanie wykresów porównujących ciągłą krzywą teoretyczną z punktami uzyskanymi drogą symulacji numerycznej.

## Wykorzystane Technologie:
Python (NumPy, Matplotlib, Numba, SciPy).
