# Medborgarförslag
Försök att samla ihop alla kommuner som har medborgarförslag. Lesson learned
* saknas API att 
  * skicka in Medborgarförslag
  * hämta ut Medborgarförslag
  * att hämta ut Medborgarförslag av viss typ eller plats
    * saknas bra översikter vad som skickas in, vad som beslutas, om vad medborgare önskar beslut 
* är idag princip 290 olika sätt att implementera [kommunallagen](https://www.riksdagen.se/sv/dokument-lagar/dokument/svensk-forfattningssamling/kommunallag-2017725_sfs-2017-725)
* finns kommuner som verkar ta emot **Medborgarförslag** men har ingen websida om detta
* 2007 skrev Sveriges Kommuner och Lnadsting ["Förenklad hantering av medborgarförslag"](https://skr.se/download/18.14995aea175214466cfbf75/1602843763296/07042.pdf)

## Wikidata ##
* egenskap Wikidata [Property:P9732](https://www.wikidata.org/wiki/Property:P9732) - "URL för medborgarförslag, URL för tjänst där medborgare can starta upprop eller lämna förslag" 
* [karta i Sverige för kommuner](https://w.wiki/3z5Q) / [lista](https://w.wiki/3$wk) / [Jupyter](https://github.com/salgo60/medborgarforslag/blob/main/Jupyter/Medborgarf%C3%B6rslag%20WIkidata.ipynb)
  * [karta kommuner utan](https://w.wiki/3z5K) wikidata egenskap P9732 dvs. vi har inte gittat spår av medborgarförslag på deras web = 76 kommuner
  * inga kommuner verkar ha API 

## Diffar [www.medborgarforslag.nu](http://www.medborgarforslag.nu/projects#)
Jämförde med Wikidata och korrigerade.

Nedan poster där jag inte hittade websida om medborgarförslag men fanns med i lista hos www.medborgarforslag.nu

|kommun              |officiell webbplats       |WD      |URL för medborgarförslag|
|--------------------|--------------------------|--------|--------------------------|
|Alvesta kommun      |http://www.alvesta.se     |Q182007 |                          |
|Eskilstuna kommun   |http://www.eskilstuna.se  |Q503144 |                          |
|Eslövs kommun      |http://www.eslov.se       |Q1130264|                          |
|Halmstads kommun    |http://www.halmstad.se    |Q504692 |                          |
|Hammarö kommun     |http://www.hammaro.se     |Q499359 |                          |
|Haparanda kommun    |http://www.haparanda.se   |Q510310 |                          |
|Karlsborgs kommun   |https://www.karlsborg.se  |Q499435 |                          |
|Kramfors kommun     |http://www.kramfors.se    |Q514815 |                          |
|Kristinehamns kommun|http://www.kristinehamn.se|Q510364 |                          |
|Pajala kommun       |http://www.pajala.se      |Q186230 |                          |
|Partille kommun     |http://www.partille.se    |Q125222 |                          |
|Svenljunga kommun   |http://www.svenljunga.se  |Q501487 |                          |
|Tierps kommun       |http://www.tierp.se       |Q510198 |                          |
|Tjörns kommun      |http://www.tjorn.se       |Q501448 |                          |
|Tomelilla kommun    |http://www.tomelilla.se   |Q515519 |                          |
