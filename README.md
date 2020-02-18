Szablon pracy inżynierskiej i magisterskiej UAM
========================

To repozytorium zawiera szablon pracy inżynierskiej i magisterskiej UAM używając pakietów **RMarkdown** i **bookdown**.
Zostało ono stworzone dla studentów Instytutu Geoekologii i Geoinformacji UAM.

## Wymagania

Działanie szablonu wymaga zainstalowania pakietu **bookdown**:

```r
install.packages("bookdown")
```

Dodatkowo konieczne jest posiadanie LaTeXa.
Najprostszą możliwością jego zainstalowania jest użycie pakietu **tinytex**:

```r
install.packages("tinytex")
tinytex::install_tinytex()
```

## Używanie szablonu

Pierwszym krokiem jest wypełnienie informacji w nagłówku pliku `index.Rmd`.
Dalej możliwe jest pisanie tekstu używając języka RMarkdown w plikach o rozszerzeniu `.Rmd`.
Wystąpienie i kolejność rozdziałów można ustalać w pliku `_bookdown.yml`.
Zbudowanie nowego pliku PDF (folder `_book`) odbywa się poprzez użycie ikonu Knit w pliku `index.Rmd`.
Więcej informacji można znaleźć pod adresem https://bookdown.org/yihui/bookdown/.

<!--references info!!-->

## Inne

Szablon opiera się o rozwiązania stworzone przez [Roba Hyndmana](https://github.com/robjhyndman/MonashThesis).
