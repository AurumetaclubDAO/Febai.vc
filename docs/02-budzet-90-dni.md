# Budżet i cashflow na pierwsze 90 dni

Stan: 11.11.2026. Materiał planistyczny, nie oferta i nie opinia podatkowa.

Kursy NBP (tabela A z 10.11.2026): **1 EUR = 4,3895 zł**, **1 USD = 3,9099 zł**. Kwoty w zł zaokrąglone do 10 zł.

## Odpowiedź w jednym akapicie

Sam eksperyment robotyczny to **2 250–6 850 zł**. Pełne 90 dni kosztuje **7 300–19 600 zł** w wariancie oszczędnym (bez rejestracji podmiotów) albo **12 100–30 500 zł** w wariancie z kompendium (z rejestracją OÜ), plus 10 970 zł kapitału zakładowego, który nie jest kosztem. Największą pozycją nie jest robot, tylko doradztwo prawno-podatkowe PL–EE.

## Oznaczenia źródeł

| Znak | Znaczenie |
|---|---|
| K | Kwota z kompendium (wcześniejszy research, niezweryfikowana ponownie) |
| W | Kwota sprawdzona w ofertach sklepów 11.11.2026 |
| Z | Moje założenie robocze, bez wyceny. Do potwierdzenia przed wydatkiem |

## 1. Mikropilotaż robotyczny

| Pozycja | Kompendium | Po weryfikacji | Źródło | Uwaga |
|---|---|---|---|---|
| Para leader–follower SO-101 | 1 300–2 500 zł | **1 550–2 650 zł** | W | Dół: zestaw serw Seeed SO-ARM101 Pro bez części 3D (ok. 352 EUR). Góra: zestaw złożony WowRobo (429–605 EUR). Nie sprawdzono VAT i dostawy |
| Części drukowane 3D | brak | 0–400 zł | Z | 0 zł przy zestawie złożonym. Przy samych serwach szkielet trzeba kupić lub wydrukować |
| Kamery, statywy, oświetlenie | 400–1 200 zł | 400–1 200 zł | K | Standard to 2 kamery (góra + nadgarstek) i stałe światło |
| Stanowisko, materiały, rezerwa | 300–2 300 zł | 300–2 300 zł | K | Płytki, siatka, blat, mocowania |
| GPU do treningu (chmura) | brak | 0–300 zł | Z | 0 zł, jeśli masz kartę NVIDIA z dużą pamięcią. Jeden użytkownik raportował ok. 18 GB przy ACT |
| **Razem** | **2 000–6 000 zł** | **2 250–6 850 zł** | | |

Cena 339,99 USD z kompendium (ok. 1 330 zł) nie znalazła potwierdzenia w ofertach. Najbliższe: 312 USD (Seeed Pro bez części 3D, wyprzedany) i ok. 433 USD (złożony, promocja).

Koszt, którego tabela nie pokazuje: czas. Montaż, kalibracja i nagranie 50–100 demonstracji to realnie kilka dni roboczych jednej osoby.

## 2. Estońska OÜ

| Pozycja | EUR | zł | Źródło | W 90 dni |
|---|---|---|---|---|
| E-Residency | 150 | 660 | K | tak |
| Rejestracja OÜ | 265 | 1 160 | K | tak |
| Adres i osoba kontaktowa (rok) | 200–400 | 880–1 760 | K | tak, płatne z góry |
| Księgowość (rok) | 600–1 200 | 2 630–5 270 | K | ok. 2 miesiące: 100–200 EUR (440–880 zł) |
| Bank, administracja, rezerwa | 285–1 250 | 1 250–5 490 | K | tak |
| Prawnik i podatki PL–EE | 1 000–2 500 | 4 390–10 970 | K | tak, przed rejestracją |
| **Pierwszy rok** | **2 500–5 765** | **10 970–25 310** | | |
| Kapitał zakładowy | 2 500 | 10 970 | K | środki spółki, nie koszt |

**Błąd w kompendium:** górna suma pozycji to 5 765 EUR, a nie 5 500 EUR.

## 3. Pozycje, których kompendium nie wycenia

| Pozycja | Kwota | Źródło | Uwaga |
|---|---|---|---|
| Fundacja w Polsce (notariusz, KRS, fundusz założycielski) | do wyceny | brak | Nie budżetuję bez oferty notariusza |
| Zgłoszenie znaku w EUIPO | ok. 850 EUR (3 730 zł) za 1 klasę | Z | Stawka z mojej wiedzy, do potwierdzenia w cenniku EUIPO. Dopiero po badaniu kolizji |
| Domeny | do wyceny | brak | Dostępności nie sprawdzano |
| Wzór umowy z rzemieślnikiem (prawa do nagrań, wizerunek, RODO) | w ramach opinii prawnej | Z | Potrzebny przed pierwszym nagraniem |

## 4. Cashflow według bramek

Wydatek uruchamia się dopiero po przejściu bramki z kompendium.

| Okres | Bramka | Wydatek | Wariant oszczędny | Wariant z kompendium |
|---|---|---|---|---|
| Dni 1–15 | przed G0 | Kontrola nazw w rejestrach (własna praca), 5–10 rozmów discovery | 0 zł | 0 zł |
| Dni 1–15 | przed G0 | Opinia prawno-podatkowa PL–EE | 4 390–10 970 zł | 4 390–10 970 zł |
| Dni 16–30 | po G0 | Rejestracja OÜ i koszty na 90 dni | 0 zł (odłożone) | 4 390–9 940 zł |
| Dni 31–60 | po G1 | Mikropilotaż robotyczny | 2 250–6 850 zł | 2 250–6 850 zł |
| Dni 61–90 | po G3 | Bez nowych wydatków, decyzja GO / PIVOT / STOP | 0 zł | 0 zł |
| | | **Suma** | **6 640–17 820 zł** | **11 030–27 760 zł** |
| | | **Z rezerwą 10%** | **7 300–19 600 zł** | **12 130–30 540 zł** |
| | | Kapitał zakładowy OÜ (nie koszt) | 0 zł | 10 970 zł |

## 5. Rekomendacja

Wybierz **wariant oszczędny**. Uzasadnienie:

1. Kompendium samo stawia bramkę G4: bez płatnego zamówienia lub listu intencyjnego nie zaciągać stałych zobowiązań. Spółka w Estonii to stałe zobowiązanie (księgowość, adres, sprawozdania).
2. Opinia PL–EE może wykazać, że OÜ zarządzana z Polski i tak podlega polskiemu CIT. Wtedy rejestracja przed opinią to wyrzucone 4–10 tys. zł.
3. Pierwszy pilotaż B2B da się sprzedać przez istniejącą działalność, jeśli taką dysponujesz.

## 6. Czego nie wolno wpisywać po stronie przychodów

- Stawek 50–200 USD za demonstrację. To szacunek dostawców usług danych, nie cena potwierdzona przez kupującego.
- Maksymalnych kwot grantów. Część programów z listy (NOWEFIO, PROO 1a) jest niedostępna dla nowej fundacji.

Przychód w budżecie pojawia się dopiero po podpisanym zamówieniu.

## Źródła cen sprzętu

- https://openelab.io/pl/products/seeed-studio-so-101-pro-servo-motor-kit-lerobot
- https://openelab.io/pl/products/wowrobo-robotics-so-arm101-diy
- https://openelab.com/products/seeed-studio-so-arm101-pro-assembled-kit-lerobot-6dof-robotic-arm
- https://botland.store/robot-arms/29177-so-arm101-pro-servo-motor-kit-a-set-of-servo-motors-for-building-the-lerobot-arm-seeedstudio-114993667.html
- https://kamami.pl/en/robotic-arms/1198708-so-arm101-low-cost-ai-arm-servo-motor-kit-pro-servo-kit-for-building-a-lerobot-robotic-arm-without-3d-elements.html
- https://dev.classmethod.jp/en/articles/lerobot-so-arm101-act-training-eval/
- https://api.nbp.pl/api/exchangerates/rates/a/eur/
