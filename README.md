# Projekat zadatak iz Baza podataka 1

## Na osnovu date specifikacije kreiran model entiteta i poveznika i napraviti konceptualni model u Oracle SQL Developer-u. 
Modelira se baza podataka košarkaškog saveza :
- Igrač igra u tačno jednom klubu, a u klubu igra više igrača.
- Klub igra utakmicu sa drugim klubom. Utakmica ima datum odigravanja, kao i rezultat (rezultat se pamti kao dva obeležja : DOMAĆIN i GOST koja označavaju broj koševa domaćina, odnosno gosta). 
    - Utakmica između dva kluba identifikuje se dodatno preko svoje šifre. Klub u utakmici može da bude domaćin ili gost.
    - Klub kao domaćin može da igra sa više klubova. Klub kao gost može da igra sa više klubova. Jedan klub sa
    - istim klubom može igrati i više utakmica, pa se svaka utakmica mora posebno zapamtiti.
    - Sudija može da sudi više utakmica. Jednu utakmicu može da sudi više sudija.
- Za svaku utakmicu pamti se ko je bio najvredniji košarkaš – MVP. (ko je bio, i koliko je koševa postigao)
- Prikaz klubova koji su pobeđivali više od nekoliko puta (broj koševa DOMAĆIN je veći od broja koševa GOST).
- Povećanje plate sudiji za 10%, ako je on sudio u više od nekoliko utakmica. 
- Brisanje klubova iz nekog mesta (izabran klub koji je igrao bar jednu utakmicu). 

## Gradivo iz BP1 u `./bp gradivo/bp.html`:
- generisanje tipa entiteta
- veznici tipa entiteta
- egzistencijalna + identifikaciona zavisnost
- veznik 3. reda, poseban slučaj, gerund i ISA hijerarhija
- prevodjenje ER modela u relacioni model
- za relacioni model se generiše DDL upit
