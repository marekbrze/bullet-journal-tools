<div align="center">

<img src="docs/logo.svg" width="56" alt="">

[English](README.md) · **Polski**

# Przeglądy

**Checklisty przeglądów papierowego notesu.<br>Otwierasz, odhaczasz po kolei, zamykasz.**

[**→ Otwórz aplikację**](https://marekbrze.github.io/bullet-journal-tools/przeglady/) &nbsp;·&nbsp; [Pobierz plik](https://raw.githubusercontent.com/marekbrze/bullet-journal-tools/main/przeglady/index.html)

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/checklist-dark.png">
  <img src="docs/checklist-light.png" width="640" alt="Checklista wieczornego przeglądu z trzema odhaczonymi krokami i rozwiniętym filtrem migracji">
</picture>

</div>

<br>

Przegląd notesu ma kilkanaście kroków i łatwo jakiś pominąć, zwłaszcza miesięczny. Ta aplikacja prowadzi przez każdy przegląd krok po kroku: najpierw to, co było, potem plan na to, co dalej. Kroki opisałem własnymi słowami na podstawie tego, jak sam prowadzę notes metodą Bullet Journal®.

## Pięć przeglądów

| | |
|:-:|---|
| **Poranek** | 8 kroków · nowy log dzienny, 3 priorytety dnia |
| **Wieczór** | 6 kroków · <code>×</code> na zrobionym, reszta przez filtr, nagłówek dnia |
| **Tydzień** | 11 kroków · refleksja na lewej stronie, zadania i intencja na prawej |
| **Miesiąc** | 15 kroków · refleksja z pytaniami, migracja, 3 + 3 |
| **Rozdział** | 8 kroków · chapter log z czterema polami, przejście do nowego notesu |

Plus **Ściąga**: symbole, filtr, zasady zapisywania w ciągu dnia i kolekcje core.

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/home-dark.png">
  <img src="docs/home-light.png" width="640" alt="Ekran główny z listą przeglądów i znacznikiem „teraz”">
</picture>
</div>

## Co potrafi

- **Pamięta, gdzie skończyłeś.** Odhaczenia zapisują się od razu. Zamkniesz kartę w połowie, wrócisz do tego samego miejsca.
- **Podpowiada, co teraz.** Rano poranek, wieczorem wieczór, tydzień po tygodniu, miesiąc na przełomie miesięcy.
- **Filtr pod ręką.** Kroki, w których przenosisz zadania, mają rozwijany filtr.
- **Historia.** Każdy zamknięty przegląd trafia do historii z czasem trwania. Przy codziennych widać serię dni z rzędu.
- **Klawiatura.** `X` odhacza następny krok, `Z` cofa, `↑` `↓` poruszają.
- **Po polsku i po angielsku.** Język dobiera się według przeglądarki, przełącznik jest w stopce. Postęp i historia zostają przy zmianie języka.
- **Prywatnie, jeden plik.** Bez konta i serwera. Pobierz `index.html` i otwórz z dysku, także offline.

<details>
<summary><b>Kopia zapasowa i przenoszenie danych</b></summary>
<br>

Dane leżą w `localStorage` przeglądarki. Pobrany plik i wersja online nie widzą swoich danych nawzajem. Do przenoszenia i kopii zapasowej służy **Eksport / Import** w stopce.

</details>

<details>
<summary><b>Jak zmienić treść kroków</b></summary>
<br>

Treść jest w obiekcie `CONTENT` na początku skryptu w `index.html`: `CONTENT.pl` to oryginał, `CONTENT.en` jego tłumaczenie. Obie wersje muszą mieć tę samą strukturę (te same id i liczbę kroków), bo postęp zapisuje się po pozycji kroku. Teksty interfejsu są w obiekcie `UI`. Każdy krok ma tytuł (`t`), opis (`d`), opcjonalną podpowiedź (`s`), flagę kluczowego kroku (`key`) i opcjonalny dodatek (`extra`: filtr, pytania, układ rozkładówki). `{•}` w tekście renderuje się jako symbol z legendy.

</details>

<br>

<div align="center"><sub>Bez instalacji · bez konta · bez śledzenia · działa na telefonie i w trybie ciemnym</sub></div>

<div align="center"><sub>Bullet Journal® jest znakiem towarowym Rydera Carrolla. To niezależny projekt, niezwiązany z autorem metody ani z bulletjournal.com.</sub></div>
