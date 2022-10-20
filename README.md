Szablon pracy inżynierskiej i magisterskiej UAM
========================

To repozytorium zawiera szablon pracy inżynierskiej i magisterskiej UAM używając pakietów oprogramowania [Quarto](https://quarto.org/).
Zostało ono stworzone dla studentów Instytutu Geoekologii i Geoinformacji UAM.
Przykład wynikowego PDFu można znaleźć [tutaj](https://raw.githubusercontent.com/spacea/amuthesis-quarto/master/docs/imienazwisko.pdf).

## Wymagania

Działanie szablonu wymaga zainstalowania [RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download) w wersji v2022.07 i wyższej.

## Używanie szablonu

Pierwszym krokiem jest wypełnienie informacji w pliku `_quarto.yml`.
Dalej możliwe jest pisanie tekstu używając języka [Markdown](https://quarto.org/docs/authoring/markdown-basics.html) w plikach o rozszerzeniu `.qmd`.
Każdy rozdział pracy dyplomowej powinien być tworzony w oddzielnym pliku `.qmd`.
W repozytorium znajduje się szereg plików `.qmd` zawierających przykładowe opisy treści rozdziałów pracy dyplomowej.
Wystąpienie i kolejność rozdziałów można ustalać w pliku `_quarto.yml`.
W pliku  `_quarto.yml` można też ustalić nazwę wynikowego pliku PDF (domyślnie jest to `imienazwisko.pdf`).
Zbudowanie nowego pliku PDF (folder `docs/`) odbywa się poprzez użycie ikony Render w RStudio.
Więcej informacji można znaleźć pod adresem https://quarto.org/docs/guide/.

## Porady

Każde zdanie napisane w plikach `.qmd` powinno zaczynać się od nowej linii. 
Dzięki temu możliwa jest łatwiejsza kontrola wersji (porównywanie zmian). 

Rozpoczęcie nowego paragrafu polega na dodaniu jednej linii przerwy (jednej pustej linii).

## Podziękowania

Szablon opiera się o rozwiązania stworzone przez [Roba Hyndmana](https://github.com/robjhyndman/MonashThesis).
