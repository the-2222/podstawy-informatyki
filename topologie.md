# Topologie sieci fizyczna

## Topologia magistrali (Bus)
**Zalety**:
*Prosta implementacja i niski koszt.*
*Łatwa rozbudowa poprzez dodanie nowych urządzeń.*
**Wady**:
*Awaria głównej magistrali powoduje zatrzymanie pracy całej sieci.*
*Ograniczona wydajność – im więcej urządzeń, tym większe przeciążenie magistrali.*



## Topologia pierścienia (Ring)
**Zalety**:
*Brak kolizji danych, ponieważ ruch odbywa się w sposób uporządkowany.*
*Stabilna wydajność przy dużej liczbie urządzeń.*
**Wady**:
**Awaria jednego urządzenia lub połączenia powoduje przerwanie działania całej sieci.*
**Trudniejsza diagnostyka i naprawa w porównaniu z innymi topologiami.*



## Topologia gwiazdy (Star)
**Zalety**:
*Łatwe diagnozowanie problemów – awaria jednego urządzenia nie wpływa na całą sieć.*
*Prosta rozbudowa – dodanie nowego urządzenia wymaga podłączenia go do centralnego węzła.*
**Wady**:
*Awaria centralnego węzła powoduje zatrzymanie całej sieci.*
*Wysokie koszty wdrożenia ze względu na potrzebę większej ilości okablowania.*





# Topologia sieci logiczna

## Punkt-punkt 
**Działanie**:
*W topologii typu punkt-punkt dane przesyłane są tylko od jednego urządzenia do drugiego. Urządzenia te mogą być podłączone ze sobą bezpośrednio, np. komputer z przełącznikiem, jak również pośrednio, na duże odległości, z wykorzystaniem urządzeń pośredniczących, czego przykładem może być połączenie ze sobą dwóch ruterów oddalonych od siebie o wiele kilometrów.*
**Zastosowanie**:
*w sieci magistrali*

## Przekazywanie żetonu 
**Działanie**:
*W topologii przekazywania żetonu, dane przekazywane są kolejno do urządzeń połączonych w sieć. Urządzenie, które otrzyma porcję danych, analizuje czy są one kierowane do niego czy też nie. Jeśli dane nie są do niego adresowane, przekazuje je dalej, do sąsiedniego urządzenia. W taki sposób, dane przesyłane są przez wszystkie urządzenia występujące pomiędzy urządzeniem źródłowym, a docelowym.*
**Zastosowanie**:
*klasyczna sieć o topologii pierścienia*

## Wielodostępowa 
**Działanie**:
*Topologia wielodostępowa (czasami zwana również logiczną topologią rozgłaszania lub magistrali) umożliwia komunikację urządzeń w sieci poprzez jedno fizyczne medium transmisyjne. Najczęściej stosowana była wspólnie z fizyczną topologią magistrali oraz gwiazdy na wczesnym etapie jej rozwoju, kiedy to stosowano jeszcze koncentratory jako punkty dostępowe do sieci.*
**Zastosowanie**:
*np.: Ethernet*

