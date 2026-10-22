# RackMetria

Simulacija IT, elektroenergetske i rashladne infrastrukture data centra.

**Predmet:** Informaciona bezbednost infrastrukturnih sistema  
**Studije:** Master akademske studije  
**Ustanova:** Fakultet tehničkih nauka, Univerzitet u Novom Sadu  
**Projekat:** 02

## Status i specifikacija

Početni repozitorijum za studentski projekat. Implementacija još nije započeta.

📄 [Tehnička specifikacija projekta](docs/RackMetria_Tehnicka_specifikacija.pdf)

PDF specifikacija je merodavna za obuhvat, zahteve i kriterijume prihvatanja. Ovaj README je uvod koji tim dopunjava tokom razvoja; pregled ispod ne zamenjuje kompletnu specifikaciju.

## O projektu

Sistem za konfiguraciju, simulaciju i analizu međuzavisnosti IT, elektroenergetske, rashladne i mrežne infrastrukture data centra.

Glavne funkcionalne celine:

- Konfigurisanje prostorija, zona, rack-ova, opreme i njihovih veza.
- Simulacija IT opterećenja, potrošnje, UPS baterije i temperaturne dinamike.
- Praćenje dostupnosti servisa, telemetrije, alarma i istorije događaja.
- Kontrolisani kvarovi, bezbednosni incidenti i poređenje scenarija.

## Kako započeti

1. Pročitajte tehničku specifikaciju, posebno arhitekturna pravila i kriterijume prihvatanja.
2. Nastavnik dodaje studente kao saradnike u ovaj repozitorijum. Prihvatite poziv za pristup kada ga dobijete.
3. Klonirajte ovaj repozitorijum:

   ```bash
   git clone https://github.com/owlCoder/rack-metria.git
   cd rack-metria
   ```

4. Rad na projektu odvija se u ovom repozitorijumu. Izmene objavljujte nakon što dobijete pristup za upis, prema dogovoru sa nastavnikom.
5. Popunite podatke o timu, izbor tehnologija i uputstvo za lokalno pokretanje.
6. Organizujte implementaciju prema granicama odgovornosti iz specifikacije i pratite zahteve kroz zadatke i testove.

## Tim

| Ime i prezime | Broj indeksa | GitHub nalog |
| --- | --- | --- |
| TODO | TODO | TODO |

**Školska godina:** TODO

## Tehnologije i arhitektura

| Oblast | Izbor i verzija |
| --- | --- |
| Backend | TODO |
| Frontend | TODO |
| Skladište podataka | TODO |
| Simulacija / integracije | TODO |
| Alati za testiranje i pokretanje | TODO |

Izbor programskog jezika i biblioteka dokumentujte u skladu sa specifikacijom. Primenite Clean Architecture i SOLID: domen, aplikacione slučajeve korišćenja, adaptere i infrastrukturu razdvojite prema njihovim odgovornostima. U README dodajte stvarnu strukturu projekta i linkove ka arhitekturnim odlukama kada budu dostupni.

## Lokalno pokretanje

TODO: Nakon dodavanja implementacije navedite:

- preduslove i tačne verzije alata;
- instalaciju zavisnosti i pripremu baze;
- potrebne promenljive okruženja i primer konfiguracije bez tajni;
- komande za pokretanje svih komponenti;
- adrese lokalnog interfejsa i API-ja;
- učitavanje demonstracionih podataka i vraćanje početnog stanja.

Lozinke, pristupne tokene i privatne ključeve ne unosite u repozitorijum.

## Testiranje i demonstracija

TODO: Dodajte komande za pokretanje testova, potrebne testne podatke i vezu između zahteva iz specifikacije i dokaza njihove provere.

Referentna demonstracija: Sala sa dva rack-a, serverima, UPS-om i rashladnom jedinicom: povećati IT opterećenje, simulirati kvar hlađenja i uporediti posledice sa scenarijem koji ima rezervnu rashladnu jedinicu.

Precizan tok demonstracije i očekivane rezultate proverite u PDF specifikaciji.

## Kontrolna lista za pripremu predaje

Ova lista pomaže organizaciji rada; kompletni kriterijumi prihvatanja nalaze se u specifikaciji.

- [ ] Popunjeni su podaci o timu i dokumentovan je izbor tehnologija.
- [ ] Dokumentovano lokalno pokretanje provereno je iz čiste kopije repozitorijuma.
- [ ] Funkcionalni i bezbednosni zahtevi povezani su sa testovima i dokazima.
- [ ] Poštovane su granice Clean Architecture slojeva i SOLID principi.
- [ ] Dokumentovani su javni ugovori, konfiguracija i obrada grešaka.
- [ ] Demonstrirano je proširenje dodavanjem novog modela opreme ili rashladne jedinice.
- [ ] Referentni scenario izvršen je kroz korisnički interfejs uz proveru događaja i API-ja.
- [ ] README odražava stvarno stanje implementacije i sadrži uputstvo za testiranje.
