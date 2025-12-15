# **1\. Wstęp**

Rynek walutowy (Forex) jest jednym z najbardziej płynnych, a zarazem zmiennych segmentów globalnego systemu finansowego. Dla polskiej gospodarki, charakteryzującej się wysokim stopniem otwartości, kursy walutowe – w szczególności USD/PLN oraz EUR/PLN – odgrywają kluczową rolę w kształtowaniu rentowności przedsiębiorstw, wartości zadłużenia zagranicznego oraz decyzji inwestycyjnych gospodarstw domowych. Ostatnia dekada (2015–2025) przyniosła szereg bezprecedensowych wydarzeń, takich jak pandemia COVID-19, wybuch wojny w Ukrainie czy globalny wzrost inflacji, które drastycznie wpłynęły na stabilność notowań złotego.

W warunkach tak dużej niepewności tradycyjne miary ryzyka, opierające się na założeniu stałej wariancji w czasie, okazują się niewystarczające. Szeregi czasowe finansowych stóp zwrotu rzadko zachowują się w sposób jednorodny; znacznie częściej obserwuje się zjawisko grupowania zmienności (ang. *volatility clustering*), gdzie po okresach dużych wahań następują kolejne okresy dużej zmienności, a po okresach spokoju – okresy wyciszenia.

### **Cel badania**

Głównym celem niniejszego projektu jest modelowanie dynamiki zmienności oraz ocena ryzyka inwestycyjnego dla par walutowych USD/PLN i EUR/PLN w latach 2015–2025. Badanie ma na celu sprawdzenie, czy zastosowanie modelu klasy GARCH (uogólnionej autoregresyjnej warunkowej heteroskedastyczności) pozwala na poprawne odwzorowanie mechanizmu kształtowania się ryzyka na polskim rynku walutowym.

Realizacja celu głównego wymaga odpowiedzi na następujące **pytania badawcze**:

1. Czy w analizowanych szeregach czasowych stóp zwrotu występuje efekt ARCH (zależność zmienności bieżącej od zmienności historycznej), uzasadniający stosowanie modeli nieliniowych?  
2. W jakim stopniu szoki zewnętrzne (innowacje) wpływają na bieżącą zmienność kursów walut, a jak silna jest "pamięć" procesu zmienności (persystencja)?  
3. Która z analizowanych par walutowych charakteryzowała się wyższym ryzykiem inwestycyjnym (wyższą zmiennością warunkową) w badanym okresie dziesięcioletnim?

### **Hipoteza badawcza**

W badaniu postawiono następującą hipotezę:

***Szeregi stóp zwrotu kursów USD/PLN oraz EUR/PLN charakteryzują się występowaniem silnego efektu skupiania zmienności, a model AR(1)-GARCH(1,1) pozwala na efektywniejszy opis ryzyka kursowego niż metody zakładające homoskedastyczność rozkładu.***

### 

### 

### **Zakres i metodyka**

Analiza empiryczna została przeprowadzona w oparciu o dzienne ceny zamknięcia (close) dla par walutowych USD/PLN oraz EUR/PLN z okresu od 2 stycznia 2015 roku do 12 grudnia 2025 roku, co daje łącznie 2831 obserwacji dla każdej zmiennej. Do weryfikacji hipotez wykorzystano model AR(1)-GARCH(1,1), estymowany metodą Największej Wiarygodności. Wybór tego narzędzia podyktowany jest jego zdolnością do jednoczesnego opisu średniej warunkowej (część AR) oraz wariancji warunkowej (część GARCH), co jest standardem w nowoczesnej ekonometrii finansowej.

