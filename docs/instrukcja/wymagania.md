---
title: "3. Dobór parametrów i wydruk modelu"
permalink: /instrukcja/krok3
---

Druk 3d oznaczeń Brajlowskich może być wymagający. W trakcie naszych testów wykonaliśmy ponad 5.000 tabliczek przez 15 miesięcy, aby porównać różne konfiguracje i opracować najlepsze metody. Poniższe informacje są wynikiem tych testów.
Uwaga!
Wszystkie nasze testy były prowadzone na drukarkach 3d firmy Prusa: Original Prusa I3 MK3S+, Original Prusa Mini+. Postaraliśmy się, aby podane tu informacje były uniwersalne, jednak mogą wymagać dostosowania dla innych maszyn, a na niektórych z nich osiągnięcie zadowalających wyników może być niemożliwe.
## Orientacja modelu
Punkt brajlowski technicznie jest elipsoidą. Gdy umieścimy tabliczkę na stole drukarki i zaczniemy druk, efekty takie jak podnoszenie się dyszy podczas retrakcji, przybliżenia wynikające z podziału modelu na warstwy czy wyciekanie materiału z dyszy sprawią, że stanie się on kłujący i nieprzyjemny w dotyku. W pewnym zakresie można próbować minimalizować ten efekt przez wybór dyszy o bardzo małej średnicy, obniżanie temperatury i zmianę ustawień retrakcji, jednak osiągnięcie zadowalających wyników w najbardziej oczywistej orientacji jest bardzo trudne.
Dlatego zalecamy drukowanie tabliczek ustawionych pionowo. Rozdzielczość osi Z jest znacznie lepsza od rozdzielczości osi X i Y. Należy pamiętać, że aby unikać przewracania się tabliczek warto włączyć brim lub raft.
## Zawartość stołu
Choć, zależnie od wielkości stołu i rozmiaru tabliczek, można ich zmieścić nawet 20-30, należy mieć na względzie ryzyko ich przewrócenia. Dlatego zalecamy umieszczanie maksymalnie 5-10 tabliczek w jednym druku.
Ryzyko przewrócenia tabliczek można zmniejszyć poprzez użycie druku sekwencyjnego, jednak drastycznie zmniejsza ono ilość elementów mieszczących się na stole.
## Zalecane ustawienia druku
### Średnica dyszy
Wysokość punktu Brajlowskiego wynosi zwykle ok. 0,5 mm. Typowa szerokość ekstruzji to ok. 110-120% średnicy dyszy. Celem uzyskania dobrych wyników, należy dążyć do sytuacji, w której obrys nie przekracza znacznie wysokości punktu. Stąd wynika, że maksymalna średnica dyszy o zadowalającej jakości druku wynosi 0,4 mm, choć zalecamy wykorzystanie dyszy o średnicy 0,25 mm.
W przypadku użycia dyszy o średnicy 0,4 mm można znacznie zwiększyć jakość druku przez użycie generatora o zmiennej szerokości obrysów (Arachne).
### Wysokość warstwy
Choć uzyskanie czytelnego Brajla jest możliwe nawet przy wysokościach rzędu 0,2 mm, w dotyku i wizualnie zauważalne stają się warstwy, co nie wygląda zbyt profesjonalnie.
Dlatego zalecamy wykorzystanie warstwy nie większej niż 0,1 mm, najlepsze rezultaty uzyskuje się przy wysokości 0,07 mm, choć wiele tańszych drukarek 3d nie pozwala na osiągnięcie takiej dokładności.
Należy jednak pamiętać, że przy wykorzystaniu wysokości warstwy poniżej 0,1 mm bardzo ważne staje się dokładne skalibrowanie maszyny oraz upewnienie się że w dyszy nie ma resztek materiału. Przy tak precyzyjnym druku bardzo wyraźne stają się błędy w tym zakresie.
### Prędkość druku
Wiele zależy od możliwości maszyny, ale zalecamy wybór prędkości w okolicy 30 mm/s, a z pewnością nie większej niż 60 mm/s.
Tabliczki mają służyć przede wszystkim dotykaniu, a więc nierówności druku będą natychmiast wyczuwalne.
### Retrakcja i temperatura
Zależnie od użytego filamentu, mogą pojawiać się nitki, w szczególności między kilkoma tabliczkami ułożonymi na stole. W tym przypadku zalecamy zwiększenie długości retrakcji i/lub nieznaczne zmniejszenie temperatury druku.
Zmniejszenie temperatury może także pomóc, gdy na kropkach Brajla osadza się zbyt wiele wyciekającego filamentu.

---

[<<<< 2. Wybór materiału](materialy.md)

[>>>> 4. (opcjonalnie) Wygładzanie chemiczne](wygladzanie.md)

---

[Wróć do strony głównej](../index.md)