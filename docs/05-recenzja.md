# Recenzja kompendium

Autor recenzji: asystent AI, 11.11.2026. To ocena biznesowa, nie opinia prawna ani podatkowa.

## Diagnoza

Kompendium jest uczciwe wobec stanu faktycznego i ma dobry mechanizm kontroli wydatków (bramki G0–G4). Jego główna wada to rozmiar: opisuje sześć filarów, dwa podmioty w dwóch krajach, czterech kandydatów do inkubacji, trzy linie produktów i trzy programy społecznościowe, a projekt nie ma jeszcze ani jednego klienta. Własny rejestr ryzyk wymienia fragmentację jako ryzyko wysokie i każe zacząć od jednej oferty B2B i jednego projektu badawczego. Plan 30/60/90 tego nie respektuje.

## Co jest mocne

1. **Tabela „ustalone / propozycja / do sprawdzenia".** Oddziela decyzje od życzeń.
2. **Bramki wydatków.** Sprzęt po rozmowach z klientami, lokal po płatnym zamówieniu.
3. **Rozdzielenie fundacji i OÜ** z zakazem ukrytego transferu korzyści.
4. **Granica „film to nie dane robota".** Chroni przed sprzedażą czegoś, czego nie da się dostarczyć.
5. **Uczciwa obietnica** zamiast „dajemy kapitał".

## Co poprawić

### 1. Rejestracja podmiotów stoi za wcześnie

Plan przewiduje rejestrację w dniach 16–30, czyli przed pierwszym przychodem. Spółka w Estonii to stałe koszty i obowiązki. Bramka G4 mówi, żeby stałych zobowiązań nie zaciągać bez płatnego zamówienia.

**Zmiana:** opinia PL–EE w dniach 1–15, rejestracja dopiero po pierwszym płatnym zamówieniu lub liście intencyjnym.

### 2. Estonia może nie dać korzyści, dla której została wybrana

Jeśli OÜ jest faktycznie zarządzana z Polski, może zostać uznana za polskiego rezydenta podatkowego lub mieć w Polsce zakład. Kompendium to ryzyko odnotowuje, ale nie rozważa alternatywy.

**Zmiana:** poproś doradcę o porównanie trzech wariantów: OÜ, polska sp. z o.o., start przez istniejącą działalność. Pytanie do doradcy brzmi „która forma jest najtańsza w utrzymaniu przy przychodzie do 200 tys. zł rocznie", a nie „jak założyć OÜ".

### 3. Domena Febai.vc kłóci się z przekazem

Końcówka `.vc` i sekcja „Inwestorom" z dokumentu nr 1 sugerują fundusz venture capital. Kompendium trzy razy zastrzega, że funduszu nie ma. Ryzyko jest reputacyjne i regulacyjne: komunikacja wyglądająca jak oferta funduszu bez zezwolenia.

**Zmiana:** `.vc` najwyżej jako przekierowanie. Domena główna na nazwie FERNHUNT, po sprawdzeniu dostępności i kolizji znaków.

### 4. Budżet ma błąd i luki

- Górna suma kosztów OÜ to 5 765 EUR, nie 5 500 EUR.
- Brak kosztów fundacji, znaku towarowego, domen, części 3D, GPU i czasu pracy.
- Brak cashflow i powiązania wydatków z bramkami.

Poprawiona wersja: [02-budzet-90-dni.md](02-budzet-90-dni.md).

### 5. Wartość danych z SO-101 jest niepotwierdzona

To moja hipoteza do sprawdzenia w rozmowach, nie fakt: dane zebrane na hobbystycznym ramieniu mogą mieć małą wartość dla producenta robotów przemysłowych, bo jego robot ma inną budowę, chwytak i czujniki. Kupujący często chce danych zebranych na własnym sprzęcie.

**Zmiana:** w każdej rozmowie discovery zadaj trzy pytania:

- Na jakim robocie muszą być zebrane dane, żebyście ich użyli?
- W jakim formacie i z jakimi czujnikami?
- Ile zapłaciliście ostatnio za dane lub ile kosztuje was zebranie ich samodzielnie?

SO-101 traktuj jako narzędzie do nauki procesu, nie jako linię produkcyjną danych.

### 6. Granty nie pomogą w pierwszych 90 dniach

NOWEFIO i PROO 1a odpadają dla nowej fundacji. Programy EIS wymagają realnej działalności w Estonii. Jedyna pozycja z bliskim terminem to PARP Laboratorium Innowatora (30.11.2026 według wcześniejszego researchu), do sprawdzenia w tym tygodniu albo skreślenia.

### 7. Brakuje liczbowych kryteriów decyzji GO / PIVOT / STOP

„Decyzja oparta na jakości danych, pilotażu i rozmowach" nie jest kryterium. Propozycja:

| Decyzja | Warunek po 90 dniach |
|---|---|
| GO | Min. 1 płatne zamówienie lub LOI na dane albo usługę Physical AI oraz polityka robota z sukcesem powyżej 60% na niewidzianych ułożeniach |
| PIVOT | Zainteresowanie jest, ale innym zadaniem, robotem lub formatem danych |
| STOP | 10 rozmów, zero gotowości do zapłaty |

Próg 60% to moja propozycja robocza, do ustalenia przed startem nagrań.

### 8. Pierwszy przychód nie potrzebuje nowej marki

Horyzont 0–12 miesięcy to wdrożenia agentów AI i automatyzacja B2B. Jeśli prowadzisz już taką sprzedaż pod inną marką, nowy szyld oznacza budowanie zaufania od zera.

**Zmiana:** zdecyduj świadomie, czy Fernhunt sprzedaje usługi B2B, czy jest warstwą R&D i marką parasolową, a usługi sprzedaje istniejąca firma.

### 9. Umowa z rzemieślnikiem przed pierwszym nagraniem

Prawa do nagrań, wizerunku i know-how to ryzyko wysokie, a wzór umowy kosztuje mało. Bez niej zebrane dane mogą być nie do sprzedania.

## Kolejność na najbliższe 30 dni

| Nr | Działanie | Koszt | Termin |
|---|---|---|---|
| 1 | Sprawdzić „Fernhunt" w TMview, EUIPO, e-Äriregister i dostępność domen | 0 zł, własna praca | tydzień 1 |
| 2 | Umówić 10 rozmów discovery: 5 z odbiorcami danych robotycznych, 5 z firmami pod wdrożenie AI B2B | 0 zł | tygodnie 1–3 |
| 3 | Sprawdzić termin i kwalifikowalność PARP Laboratorium Innowatora | 0 zł | tydzień 1 |
| 4 | Konsultacja podatkowa PL–EE z porównaniem trzech form | 4 390–10 970 zł | tydzień 2 |
| 5 | Jedna płatna oferta B2B z ceną i zakresem | 0 zł | tydzień 2 |
| 6 | Wzór umowy z rzemieślnikiem | w ramach pkt 4 | tydzień 3 |
| 7 | Decyzja o formie prawnej i o zakupie SO-101 | zależnie od wyniku 2 i 4 | tydzień 4 |

## Czego nie robić w tym czasie

- Nie rejestrować fundacji ani OÜ.
- Nie zgłaszać znaku przed badaniem kolizji.
- Nie pisać wniosków grantowych „na Fernhunt" bez konkretnego projektu.
- Nie zatwierdzać logo. To nie blokuje sprzedaży.
- Nie uruchamiać Fernhunt Night, Academy ani Baltic AI Bridge.
