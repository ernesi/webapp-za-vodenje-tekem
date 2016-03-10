# Zahodna Liga - web aplikacija za vodenje tekem

Ideje:
- online skozi dostopna
- offline simple delovanje + sync upstream, za izvedbo tekme (vagrant up za postavitev celotnega VMja in sistema lokalno)
- celotno vodenje izvedb: razpis, prijave, samo tekmovanje, rezultati
- ...

PROCES:
Koordinator izvede otvoritev sezone: arhiviranje stare sezone, otvoritev nove sezone, vnese tekme, prijavi nove (ali aktivira že vnesene) klube.
Tekmovalci se prijavijo v klubu. Predstavnik kluba nove prijavi (ali aktivira že vnesene). Ažurira podatke o licencah (možnost avtomatske povezave s PZS) in članarinah.
Pred začetkom tekme prijavi izbrane aktivne tekmovalce na vsako posamezno tekmo. Po roku za oddajo prijav se izpiše plačilni nalog in se ga pošlje klubu (mail)
Kreirajo se štartne liste po pravilu prvih pet po vrstnem redu najboljših iz lanske sezone, ostali naključno)
Možnost naknadnih prijav??? (če da, se jih doda na konec štartne liste).
Pred štartom delegat/sodnik aktivira tekmo, vnese potrebne parametre (višine smeri ipd.) Po korakih vnos rezultatov (možnost s tablico, pametnim telefonom, računalnikom) neuradni rezultati, uradni rezultati, zaključek tekme pripelje tekmo do konca.
Rezultati se vidijo na spletni strani. Ažurirajo se tudi skupni rezultati.
Po zadnji tekmi koordinator zaključi sezono in razglasi skupne rezultate (po sistemu število vseh tekem – dve (oz. po formuli glede na število tekem))
Dogovoriti je potrebno še sistem morebitne zamenjave koordinatorja.

Potrebno je zagotoviti naslednje programske sklope:
•	Centralno evidenco tekmovalcev
•	Centralno evidenco klubov
•	Vodenje tekme
o	Balvan
o	Hitrost
o	težavnost
•	Vodenje rezultatov tekem in skupnih rezultatov

CENTRALNA EVIDENCA TEKMOVALCEV
Vzpostavi se baza podatkov o tekmovalcih. Obvezni podatki so ime, priimek, EMŠO, klub, letnica rojstva, kategorija (vezana na letnico rojstva) (vedeti je treba, da smo že imeli situacijo, ko sta dva tekmovalca imela enako ime, priimek, kategorijo in klub), status (za posamezno sezono se določi ali je tekmovalec aktiven ali neaktiven in mogoče še trajno neaktiven), licenca (A,B), plačana članarina PD (nečlani ne morejo tekmovati)
V bazi otrok bo potrebno označiti status aktivnosti:
Aktiven: tekmuje v sezoni
Neaktiven: v tekoči sezoni ne tekmuje. Ni izključeno, da ne bo tekmoval v prihodnosti
Trajno neaktiven: v tekoči sezoni ne tekmuje in v prihodnosti ne bo več tekmoval – starejši od 17 let
Status ureja predstavnik kluba. Vnos 
Izbor kategorije:
Kategorija je vezana na letnico rojstva in jih za tekočo sezono določi koordinator

CENTRALNA EVIDENCA KLUBOV
Vzpostavi se baza podatkov o klubih. Obvezni podatki so naziv kluba, naslov, kraj, načelnik, mail, telefon, predstavnik kluba, mail, telefon, plačnik (če je klub sekcija), status, član KŠP in član PD (če klub ni član PD in KŠP se ne more registrirati v ZL)
STATUS: Aktiven sodeluje v tekoči sezoni, neaktiven ne sodeluje v tekoči sezoni

VODENJE TEKME
Zagotoviti je potrebno podporo za tri različne discipline in podrediti izvajanje tekme pravilniku discipline (Težavnost: dve smeri, če je prva preplezana gre lahko v drugo (opcija tudi brez pogoja, da je prva preplezana), opcija superfinale.
Balvan je že naredila Radovljica, hitrost: dvojice, izpadanje, pravila kdo s kom tekmuje,… )

VODENJE REZULTATOV TEKEM IN SKUPNIH REZULTATOV
Ko se tekma zaključi, se osvežijo še skupni rezultati. Vse skupaj se objavi na spletni strani.

Uporabniki:
1.	ADMIN
2.	KOORDINATOR
3.	PREDSTAVNIK KLUBA
4.	TEKMOVALCI 
5.	SODNIKI, DELEGATI TEKME

1.	ADMIN

•	Dostop do vsega???

2.	KOORDINATOR

•	Potrjuje spremembo podatkov o klubih
•	Otvoritev sezone (štartnina, kotizacija), razpiše tekme (datum, kraj, organizator), določi kategorije (po letnicah)
•	Zaključek sezone in razglasitev skupnih rezultatov

3.	PREDSTAVNIK KLUBA
•	Vnesejo tekmovalce za svoj klub in njihove podatke, določajo status tekmovalca, prijavljajo tekmovalce na posamezne tekme

4.	TEKMOVALCI
•	Tekmovalci imajo možnost urejanja lastnih podatkov (s potrditvijo predstavnika kluba)
5.	SODNIKI, DELEGATI TEKME
•	Otvoritev tekme, vnos rezultatov, neuradni rezultati, razglasitev (uradni rezultati, ki se ne spreminjajo več), zaključek tekme

