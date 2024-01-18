Projekat se sastoji iz 4 faze: pravljenje leksera, parsera, sintaksne analize i generisanja koda.

Saveti za izradu projekta:

Najbolje je prvo odslušati sva četiri snimka i samostalno odraditi zahteve sa njih. Tako ćete donositi pametnije odluke u ranijim fazama, a to će se ogledati na naredne!
Na primer, u mom kodu, gramatičke smene nisu pametno odrađene pa sam došao u situaciju da u semantičkom prolazu moram da kopiram kod više puta na više mesta. Imajte na umu da su snimci lošeg kvaliteta,
malo šta je u njima objašnjeno.

Takođe, treba obratiti pažnju na same uslove po nivoima jer nisu jasno naznačeni. Ja sam nameravao da radim samo nivo A, pa sam na kraju, zbog nejasnih zahteva odradio i preko toga bez potrebe (npr. pozive funkcija).

Pre odbrane obavezno pogledati koji su argumenti za runovanje kojih fajlova jer ćete to morati sami na licu mesta da konfigurišete.

Modifikacija za A nivo u januaru 2024. godine je bila korektna: Bilo je potrebno da se uvede ključna reč USING i to u smeni za Statements: USING IDENT:namespace SEMICOLON
Ako tražena promenljiva ne postoji u navedenom namepsaceu, onda se posmatra default namespace. Ako namespace ne postoji, baca se greška (iz semantičkog prolaza, nema generisanja koda). Ako imamo više using naredbi,
efektivna će biti samo poslednja. Nakon korišćenja using naredbe se ne možemo vratiti u default opseg.

U prilogu se nalazi specifikacija MikroJave i postavka projekta za januar 2024. godine.
