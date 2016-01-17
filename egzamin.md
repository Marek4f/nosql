#Marek Eggert

Specyfikacja komputera

System: Windows 10 64bit

procesor: i7 4800MQ 2.70ghz

RAM: 16GB

Dysk: wd10jpvx-75 scsi, Cache: 8mb, Rotation Speed: 5400 RPM, Model: Blue

Zaimportowalem baze [restauracje.json](https://dl.dropboxusercontent.com/u/15056258/mongodb/restaurant.json) poleceniem 
mongoimport --db bazka --collection res --drop --file res.json
Zostala zaimportowana natychmiast. Poleceniem
db.res.count()
zliczylem wszystkie rekordy.
![GitHub Logo](e1.png)

#sortowanie

Wyswietlenie 5 restauracji zaczynajacych sie na "A" wyswietlajac od najgorszej oceny

![GitHub Logo](e2.png)

Wyswietlenie 5 restauracji serwujacych pizze w Londynie

![GitHub Logo](e3.png)

#agregacje

Wyswietlenie 15 najczesciej powtarzajacych sie nazw restauracji

![GitHub Logo](e4.png)

wyswietlenie srednich ocen dla restauracji

![GitHub Logo](e5.png)

#Javascript

Wyswietlenie restauracji majacych dlugosc nazwy serwowanego jedzenia dluzsza niz 3 znaki

![GitHub Logo](e6.png)

Wyswietlenie adresow url restauracji serwujacych pizze i majace maksymalna ocene

![GitHub Logo](e7.png)

Wyswietlenie 3 najczesciej dawanych ocen za pomoca grupowania

![GitHub Logo](e8.png)

Wyswietlenie 3 najczestrzych lokacji

![GitHub Logo](e9.png)
