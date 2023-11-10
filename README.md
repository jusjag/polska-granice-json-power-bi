# Mapy Polski do użytku w Power BI
Granice Polski gotowe do użytku w Power BI / Power BI ready files of Polish boundaries

### Warunki użytkowania:
Wszystkie te dane są publicznie dostępne a moja praca polegała wyłącznie na dostosowaniu pliku.<br>
Bierz i korzystaj ku chwale ojczyzny :) Pamiętaj, że te dane mają charakter jedynie poglądowy i nie mają żadnej mocy prawnej.<br>
Będzie mi miło jeśli oznaczysz źródło, ale nie jest to wymagane.<br>

### Zobacz też
Mapy dzielnic polskich miast dostosowane do użytku w Power BI - <a href="https://github.com/jusjag/dzielnice-json-power-bi/tree/main">link</a>.

## Gdanice Województw
<a href="https://github.com/jusjag/polska-granice-json-power-bi/blob/main/Polska_wojewodztwa.json">POBIERZ</a><br>
![alt text](https://github.com/jusjag/polska-granice-json-power-bi/blob/main/PL-wojewodztwa.png?raw=true)<br>
<br>ŹRÓDŁO: Państwowy Rejestr Granic (https://dane.gov.pl/pl/dataset/726,panstwowy-rejestr-granic-i-powierzchni-jednostek-podziaow-terytorialnych-kraju/resource/29515/table)<br>
Data dostępu: 10.11.2023<br>

# Miasta i gminy
<a href="https://github.com/jusjag/polska-granice-json-power-bi/blob/main/Polska_miasta_gminy.json">POBIERZ</a><br>
<br>ŹRÓDŁO: Państwowy Rejestr Granic (https://dane.gov.pl/pl/dataset/726,panstwowy-rejestr-granic-i-powierzchni-jednostek-podziaow-terytorialnych-kraju/resource/29515/table)<br>
Data dostępu: 10.11.2023<br>

# Jak używać?
1. Pobierz wybrany plik.
2. Upewnij się, że Twoje dane zawierają kolumnę z nazwami jednostek (dzielnic/województw/itp) (do pobrania np. z Wikipedii przez Power Query).
3. Utwórz nową wizualizację "shape map" używając danych z tej właśnie kolumny.<br><br>
![alt text](https://github.com/jusjag/dzielnice-json-power-bi/blob/main/HowTo_1.png?raw=true)<br>
5. Pojawi się mapa USA. Nie przejmuj się :)
6. Zaznacz mapę, w panelu "Format" przejdź do "Map settings" i rozwiń listę pod "Map type".<br><br>
![alt text](https://github.com/jusjag/dzielnice-json-power-bi/blob/main/HowTo2.png?raw=true)<br>
8. Na samym dole listy znajduje się pozycja "Custom map".

# Uwagi
Choć zakładam, że zamieszczone dane są poprawne, szczególnie że opieram się na źródłach rządowych, nie odpowiadam za ich zgodność ze stanem rzeczywistym.
10. Po wybraniu tej opcji poniżej pojawi się pole "add a map type" z opcją załadowania pliku.
11. Załaduj plik pobrany na początku.
12. Upewnij się, że nazwy jednostek są w polu "Location" (czasem automatycznie ładują się jako "Legend").<br>
![alt text](https://github.com/jusjag/dzielnice-json-power-bi/blob/main/HowTo3.png?raw=true)<br>
13. Voila!
14. W panelu "Build visual" pojawi się pole "Color saturation", którego możesz użyć by zróżnicować kolory.
