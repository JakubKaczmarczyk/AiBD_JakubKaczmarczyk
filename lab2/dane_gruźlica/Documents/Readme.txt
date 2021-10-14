Dane do analizy pochodzą ze źródła: https://github.com/KAIR-ISZ/public_lectures/blob/master/Analiza%20i%20Bazy%20Danych%202021/Lab%202/Datasets/tb.csv.
Plik 'data_processing.ipynb' wykonuje na oryginalnych danych wstępne działania takie jak poprawne nazwanie kolumn, zamianę wartości
NaN na zera oraz usunięcie niepotrzebnaych kolumn oraz niepoprawnych wierszy. 
Dane zostały podzielone na 3 tabele - osobną zawierającą sumę odnotowanych przypadków w danym roku i kraju dla wszystkich grup wiekowych i płci
oraz dwie tabele, osobne dla mężczyzn i kobiet, z podziałem liczby zachorowań na grupy wiekowe.
Przetworzone dane zapisane zostały w katalogu Data Analysis.
Plik 'data_analysis.ipyng' dokonuje analizy danych, zlicza łączną ilość zachorowań na gruźlicę w każdym z krajów na przedziale 
lat 1989-2008, w których prowadzone było badanie. Generowane są również wykresy pozwalające łatwiej odczytać wyniki obliczeń.