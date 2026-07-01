________________________________________
<div align="center">

<b>
Wejście spółki do renomowanego indeksu – przepis na „łatwy” zysk czy „pułapka” na mniej doświadczonych inwestorów?</b>

</div>

________________________________________
Materiał na youtube: https://www.youtube.com/watch?v=waVLqRRszhY


**Opis problemu**:

Rewizje indeksu niosą za sobą istotne konsekwencje dla spółek – akcje firm, które dołączają do indeksu, muszą zostać doważone przez fundusze pasywne, co generuje dodatkowy popyt na walory firmy.



Co więcej, spółki trafiające do indeksu znajdują się zazwyczaj w silnym momentum wzrostowym (co często wspiera kontynuację trendu), ich sytuacja finansowa jest z reguły lepsza niż jeszcze kilka kwartałów wcześniej, a rosnąca rozpoznawalność może być dodatkowym katalizatorem przyszłych wzrostów kursu.



Wykorzystując dane dotyczące zmian w składzie S&P 500 z lat 1996–2025, sprawdziłem, jak zachowywały się ceny akcji podmiotów, które trafiły do indeksu. Analiza dotyczyła zarówno okresu przed dołączeniem do indeksu, jak i po jego wejściu w życie (effective date).

**Założenia**:

- w dniu wejścia spółki do indeksu wykorzystano cenę Adjusted OPEN - Adjusted Price uwzględnia wszystkie zjawiska mogące zniekształcać dane jak np. split akcji, dywidendy. Unikamy dzięki temu sztucznych ruchów cen

- wszystkie pozostałe ceny akcji to ceny Adjusted CLOSE z 5 sesji wstecz, 20 sesji wstecz (jako miesiąc wstecz), 60 sesji wstecz (jako 3M wstecz), 20 sesji do przodu (jako miesiąc do przodu) oraz 60 sesji do przodu (jako 3M do przodu)

- w badaniu nie uwzględniono spółek, które zostały zdjęte z giełdy – wynika to z ograniczeń darmowej wersji yahoo finance

- pobrane dane S&P 500 z wykorzystaniem tickera ^GSPC obejmują analogiczne przesunięcia w czasie jakie przedstawiono wyżej dla spółek dołączających do indeksu



**Źródła danych**:

- biblioteka yfinance (yahoo finance)

- kaggle – skład indeksu S&P 500 (z uwzględnieniem zmian)

________________________________________

**Podsumowanie i wnioski dla inwestora**:

1.	Okres 1–3 miesięcy przed wejściem do indeksu historycznie charakteryzował się silnym momentum i wysoką relatywną stopą zwrotu względem benchmarku.

2.	Okres bezpośrednio po wejściu do indeksu (1M–3M) statystycznie nie zapewniał przewagi względem rynku – często następowało wyhamowanie momentum i mean reversion.

3.	Krótkie okno wokół ogłoszenia decyzji dawało dodatnie stopy zwrotu głównie w latach wcześniejszych; po 2010 r. efekt wyraźnie osłabł.

4.  Kluczowym wyzwaniem pozostaje trafne wytypowanie spółki, która rzeczywiście trafi do indeksu.
