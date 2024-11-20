# Tema 2: Quick Time

## Descriere

In aceasta tema, se va crea un joc de reflex competitiv pentru doi jucatori, in care cei doi participanti vor concura pentru a obtine cel mai mare punctaj, testandu-si viteza de reactie. Fiecare jucator va avea butoane si LED-uri proprii, iar jocul se va desfasura in mai multe runde. Scopul fiecarui jucator este sa apese cat mai rapid butonul corespunzator culorii afisate pe LED-ul RGB al echipei sale. Punctajul fiecarui jucator va fi afisat pe un ecran LCD si se va actualiza pe parcursul jocului. La final, jucatorul cu cel mai mare punctaj va fi declarat castigator.

### Cerinte: 

**SPI**<br>
Tema necesita utilizarea a doua placi Arduino Uno care comunica prin SPI, deoarece un singur Arduino nu ofera suficienti pini GPIO. Arduino-ul master controleaza LCD-ul, servomotorul si gestioneaza starea jocului (punctaj, LED-uri active). Arduino-ul slave controleaza butoanele si LED-urile, primind comenzi de la master si trimittand inapoi informatii despre butoanele apasate.

**Butoane**<br>
Orice buton incepe jocul. In timpul jocului, butoanele trebuie folosite doar pentru controlul jocului si nu trebuie sa reseteze progresul. Doar butoanele jucatorului activ in acea runda pot controla jocul.

**LED-uri**<br>
Fiecare buton are asociat un LED de o culoare diferita. Pe parcursul jocului acestea trebuie sa fie aprinse pentru a vedea carei culoare ii corespunde fiecare buton
LED-ul rgb trebuie să se aprinda in una din cele 3 culori ale butoanelor
LED-ul rgb trebuie sa fie stins daca nu este runda jucatorului corespunzator acelui LED

**LCD**<br>
Pentru controlul acestuia am folosit biblioteca <LiquidCrystal>
Vor fi folositi doar pinii D4-7 pentru liniile de date ale ecranului
Pe parcursul jocului trebuie sa afiseze punctajele celor 2 jucatori

**Servomotor**<br>
Servomotorul va incepe de la pozitia de 0 grade si se va deplasa in sens antiorar pentru a indica scurgerea timpului.

### Componente:

- <b>6x LED-uri (2 grupuri de câte 3 leduri, în cadrul unui grup trebuie să avem culori diferite)<b> 
- <b>2x LED RGB (1 pentru fiecare jucător)<b> 
- <b>6x butoane (3 pentru fiecare jucător)<b>
- <b>2 x Rezistoare 1kΩ<b>
- <b>x LCD<b>
- <b>1x servomotor<b>
- <b>2x Breadboard<b>
- <b>Fire de legatura<b>
- <b>2x Arduino Uno<b>

## Poze ale setup-ului fizic

*TODO*

## Schema electrica

*TODO*

## Functionalitate montaj

*TODO*

