# Supply Chain Optimization Using Genetic Algorithms

## Opis repozytorium

Repozytorium zawiera implementację algorytmów genetycznych zastosowanych do rozwiązania autorskiego problemu logistycznego oraz porównanie wyników ze zbliżonym problemem CVRP (Capacitated Vehicle Routing Problem) rozwiązanym przy użyciu narzędzia OR-Tools. Dane oraz implementacje bazują na mapie miasta Krakowa i są częścią pracy inżynierskiej pt. "Optymalizacja łańcucha dostaw z wykorzystaniem algorytmów genetycznych".

## Struktura repozytorium

- **`problem-logistyczny.ipynb`**  
  Plik Jupyter Notebook zawierający pełną implementację algorytmów genetycznych oraz funkcje niezbędne do rozwiązania problemu logistycznego. Notatnik zawiera także porównanie wyników algorytmów genetycznych z rezultatami uzyskanymi za pomocą OR-Tools.  
  > **Uwaga:** Wyniki zapisane w pliku `ipynb` mogą różnić się od tych opisanych w pracy inżynierskiej. Pomimo ustawienia tego samego ziarna, możliwe są niewielkie różnice wynikające z:
  > - Aktualizacji używanych bibliotek,
  > - Niedoskonałej stabilności algorytmów genetycznych.

- **`wizualizacje/`**  
  Folder zawierający interaktywne mapy Krakowa w formacie HTML, które przedstawiają optymalne trasy pojazdów dla różnych podejść:
  - **`algorytmy-genetyczne/`**  
    Zawiera wizualizacje tras wygenerowanych przy użyciu algorytmów genetycznych.
  - **`or-tools-cvrp/`**  
    Zawiera wizualizacje tras wygenerowanych przy użyciu OR-Tools dla zbliżonego problemu CVRP.

- **`cache/`**  
  Folder pomocniczy zawierający dane pośrednie, takie jak cache wyników obliczeń.

- **`README.md`**  
  Niniejszy plik, opisujący strukturę repozytorium i jego zawartość.

## Przeznaczenie repozytorium

Repozytorium jest częścią pracy badawczej i edukacyjnej, mającej na celu zrozumienie działania algorytmów genetycznych w kontekście problemów logistycznych. Może być wykorzystane jako materiał edukacyjny, przykład implementacji algorytmów metaheurystycznych lub punkt wyjścia do dalszych badań w zakresie optymalizacji.

## Wymagania

- Python 3.8 lub nowszy
- Biblioteki:  
  - `numpy`
  - `matplotlib`
  - `osmnx`
  - `folium`
  - `NetworkX`
  - `DEAP`
  - `ortools`

## Uruchamianie wizualizacji

Aby otworzyć wizualizacje znajdujące się w folderze `wizualizacje`, wystarczy uruchomić odpowiedni plik `.html` w przeglądarce internetowej.

