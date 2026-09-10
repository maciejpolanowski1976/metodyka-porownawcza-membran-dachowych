# Metodyka porównawcza systemów membranowych PVC, TPO i EPDM dla dachów płaskich

## Cel projektu

Projekt przedstawia uporządkowaną metodykę porównawczą systemów membranowych stosowanych na dachach płaskich, ze szczególnym uwzględnieniem PVC/PVC-P, TPO/FPO i EPDM.

Celem opracowania jest stworzenie przejrzystych ram oceny umożliwiających:
- porównanie cech technicznych systemów,
- analizę zgodności danych pochodzących z różnych źródeł,
- rozróżnienie cech rodziny materiałowej od cech konkretnego produktu,
- ocenę porównywalności parametrów deklarowanych według różnych norm,
- dokumentowanie podstaw źródłowych użytych w analizie.

Projekt nie stanowi instrukcji projektowej ani rekomendacji dla konkretnego obiektu. Ostateczny dobór rozwiązania powinien uwzględniać dokumentację projektową, aktualną dokumentację producenta, obowiązujące normy i wymagania właściwe dla danego obiektu.

## Zakres projektu

Repozytorium zawiera:
- zestaw kategorii porównawczych dla PVC/PVC-P, TPO/FPO i EPDM,
- rejestr źródeł technicznych,
- jakościową macierz decyzyjną,
- zasady porównywalności danych,
- metodę porównania konkretnych produktów,
- pierwsze porównanie reprezentatywnych produktów,
- scenariusze zastosowań dla wybranych typów obiektów,
- dokumentację metodologiczną i ograniczenia analizy.

## Aktualny status

Aktualna wersja: `v0.3.0`

Na tym etapie projekt obejmuje zarówno porównanie rodzin materiałowych, jak i pierwsze porównanie konkretnych produktów:
- Sarnafil S 327-12 L - PVC,
- Sure-Weld TPO Reinforced Membrane - TPO,
- Sure-Seal EPDM 60 mil - EPDM.

Nie utworzono rankingu produktów. Parametry oparte na różnych metodach badawczych są oznaczane jako nieporównywalne lub porównywalne w ograniczonym zakresie.

## Struktura

```text
dane/
dokumentacja/
metodologia/
przyklady/
README.md
CITATION.cff
LICENSE
CHANGELOG.md
SPIS_TRESCI.md
```

## Zasady

1. Parametr konkretnego produktu nie jest automatycznie przypisywany całej rodzinie materiałowej.
2. Dane liczbowe są porównywane tylko wtedy, gdy metody badawcze i warunki oceny są zgodne.
3. Brak danych nie jest zastępowany szacunkiem.
4. Dokumentacja producenta jest traktowana jako źródło pierwotne dla deklarowanych właściwości danego produktu.
5. Wnioski są ograniczane do zakresu dostępnych źródeł.

## Cytowanie

Informacje do cytowania znajdują się w pliku `CITATION.cff`.

## Licencja

Projekt udostępniono na licencji CC BY 4.0.
