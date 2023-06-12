1. DataScienceWSB
Projekt Dyplomowy na kierunku Python Developer na WSB Merito w Gdańsku - Data Science
Celem analizy była poprawna interpretacja danych dla wypadków komunikacyjnych w Nowym Yorku
Zastosowano: pandas, matplotlib, seaborn, jupyter (instrukcje pisane w języku Python w IDE PyCharm na systemie Linux: Dystrybuja Ubuntu)

2. URUCHOMIENIE
Został przygotowany plik requirements.txt
Można go uruchomić z poziomu IDE lub urzywając komendy w termilanu:
$ pip install -r requirements.txt
dokumentacja w PhyCharm: 
https://www.jetbrains.com/help/pycharm/managing-dependencies.html#populate_dependency_files
WAŻNE! 
projekt zakłada istnienie źródła dancyh w folderze Data. Ponieważ plik jest zbyd duży do uploadu na git należy upenić się, że znajduje się w folderze.
Nazwa adekwatna z tym udostepnionym studnentom na dysku Goolde:
File_source = '../Data/nypd-motor-vehicle-collisions.csv'
dla przygotowania danych każda komórka dla wygody ma zakomentowaną sekcję "RESET"

3. ZAKRES
Projekt został podzielony na trzy rozdziały:
Rozdział I analiza struktury danych
  rozpoznanie i charakterystyka zbioru danych - pozostawiono najważniejsze instruckje
  identyfikacja i diagnoza podstawowych problemów
Rozdział II interpretacja danych i definicje
  wstępna analiza będąca źródłem definicji i interpretacji we właściwej analizie
  rozstrzygnięcie problemów z danymi
Rozdzial III analiza właściwa:
  budowa definicji zbiorów danych i postawionych problemów
  =>Określić najniebezpieczniejsze czynniki wypadków w danej dzielnicy NY
  =>Dowiedzieć się, ile zgonów oraz obrażeń zostało spowodowanych przez szybką jazdę
  ogólnie, oraz w danej dzielnicy
  =>Określić top 5 najniebezpieczniejszych czynników wypadków
  =>Wygenerować wizualizację określającą ilość wypadków z podziałem na dni tygodnia
  
  
