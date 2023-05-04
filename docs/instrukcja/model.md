---
layout: page
title: "1. Utworzenie komputerowego modelu 3d tabliczki"
permalink: /instrukcja/krok1
---

Druk 3d zaczyna się zawsze od modelu. W pierwszej kolejności należy postawić sobie pytanie, jakie elementy powinny znaleźć się na tabliczce.
Może być to oczywiście tylko Brajl. Można też umieścić informacje czarnodrukową, kod QR, tagi NFC lub dowolne inne elementy.
## Wykonanie modelu
Alfabet Brajla nie jest kodem znak do znaku. W sześciopunkcie da się zapisać jedynie 63 różne kombinacje. Dlatego istnieją znaki specjalne (np. znak wielkiej litery), a niektóre litery i znaki interpunkcyjne różnią się zależnie od języka.

By uprościć cały proces, udostępniliśmy program o nazwie [CrystalDot](https://github.com/dawidpieper/CrystalDot/releases/latest). To proste narzędzie automatycznie tworzy tabliczkę z wykorzystaniem podanego tekstu, rozmiaru czcionki Brajlowskiej i języka.
Domyślnie stosowane wymiary to czcionka Marburg Medium, najpowszechniej stosowana w Polsce.

** Wskazówka: w programie "CrystalDot" można wygenerować tabliczkę o zerowej grubości. Spowoduje to stworzenie jedynie pliku składającego się z punktów, które następnie można umieścić w dowolnym innym modelu. **
## Kod QR, czarnodruk i inna zawartość
Program "CrystalDot" nie pozwala na dodawanie do tabliczek innych elementów.
W Fundacji wykorzystujemy w tym celu dość skomplikowany skrypt napisany na nasze wewnętrzne potrzeby. Obecnie pracujemy nad jego udokumentowaniem i udostępnieniem.

Tym czasem możliwe jest utworzenie tych elementów ręcznie w dowolnym edytorze CAD, a nawet w niektórych slicerach.

** Uwaga: w celu naniesienia elementów kontrastowych lub kodów QR wymagane jest użycie drukarki mogącej drukować z kilku materiałów jednocześnie. **

---

[<<<< Strona Główna](../index.md)

[>>>> 2. Wybór materiału](materialy.md)