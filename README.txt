CZYŚCIUTKO — strona demo (pranie tapicerki)
=================================================

To jest wersja demonstracyjna. Wszystkie dane kontaktowe, ceny i zdjęcia
są PRZYKŁADOWE — trzeba je podmienić na prawdziwe przed publikacją.

PLIKI
-----
  index.html      – strona główna (co robimy, jak to działa, opinie)
  cennik.html     – cennik (prawdziwe ceny od klienta)
  przed-po.html   – galeria "przed i po" (opisane miejsca na zdjęcia)
  o-nas.html      – o firmie
  style.css       – wygląd całej strony (kolory zmieniasz na górze, w :root)
  main.js         – menu na telefonie i drobne rzeczy

CO PODMIENIĆ PRZED ODDANIEM
---------------------------
  [ ] Telefon: w plikach jest 572 188 716 (z ulotki).
      Szukaj: tel:+48572188716  oraz  572 188 716
  [ ] E-mail: kontakt@czysciutko.pl  -> wstaw prawdziwy
  [ ] Adres w stopce: "ul. Przykładowa 1, 05-120 Legionowo" -> prawdziwy
      (jeśli to usługa tylko z dojazdem, można zostawić sam obszar działania)
  [ ] Miasto: w tekstach jest "Legionowo" -> zmień, jeśli inne
  [ ] Godziny otwarcia w stopce
  [ ] CENY w cennik.html – już uzupełnione realnymi stawkami
  [ ] Liczby w "O nas": XXX upranych mebli, X lat na rynku
  [ ] ZDJĘCIA: w miejscach z napisem "Miejsce na zdjęcie" / "PRZED" / "PO"
      wstaw prawdziwe fotki. Format WebP, do 150 KB, dodaj alt.
  [ ] Schema.org w index.html (sekcja <script type="application/ld+json">)
      – te same dane co wyżej.

JAK PODMIENIĆ ZDJĘCIE
---------------------
  Zamiast bloku <div class="ph" ...>...</div> wstaw:
  <img src="nazwa-zdjecia.webp" alt="opis zdjęcia" width="800" height="600" loading="lazy">
  (pierwsze zdjęcie na stronie: loading="eager" fetchpriority="high")

PODGLĄD
-------
  Otwórz index.html w przeglądarce (dwuklik) albo użyj podglądu na żywo.
