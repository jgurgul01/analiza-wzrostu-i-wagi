Opis Działania Programu
Program działa w środowisku Jupyter Notebook i służy do analizy danych dotyczących wzrostu i wagi osób. Analiza obejmuje eksploracyjną analizę danych (EDA), modelowanie regresji liniowej i wielomianowej oraz wizualizację wyników. Celem programu jest zrozumienie, jak wzrost i waga są ze sobą powiązane oraz jakie wnioski można wyciągnąć z tych danych.

Kroki Działania Programu
Importowanie Bibliotek:

Importowanie niezbędnych bibliotek do analizy danych, wizualizacji, modelowania oraz zapisywania modelu.
Pobieranie Danych:

Pobranie danych z publicznego źródła internetowego i wczytanie ich do DataFrame za pomocą pandas.
Zmiana Nazw Kolumn i Konwersja Jednostek:

Zmiana nazw kolumn na polskie oraz konwersja jednostek wzrostu z cali na centymetry i wagi z funtów na kilogramy.
Eksploracyjna Analiza Danych (EDA):

Wyświetlanie podstawowych informacji o danych, w tym nazwy kolumn, typy danych oraz statystyki opisowe.
Tworzenie wykresów rozkładu dla wzrostu i wagi oraz wykresu rozproszenia.
Obliczanie współczynnika korelacji między wzrostem a wagą.
Oczyszczanie Danych:

Usuwanie brakujących wartości, aby zapewnić kompletność danych do analizy.
Modelowanie:

Przygotowanie danych do modelowania poprzez podział na zestawy treningowe i testowe.
Tworzenie modelu regresji liniowej oraz regresji wielomianowej.
Ocena modeli za pomocą średniego błędu kwadratowego (MSE) i współczynnika determinacji (R^2).
Wizualizacja wyników modeli.
Zapisanie Modelu:

Zapisanie wytrenowanego modelu regresji liniowej do pliku za pomocą biblioteki joblib.
Wyjaśnienie Wyników Analizy i Modelowania:

Wyświetlanie podsumowania wyników analizy, w tym rozkładu wzrostu i wagi oraz wyników modeli regresji.
