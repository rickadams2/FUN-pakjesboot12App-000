**Project uitleg**
Sinterklaas wil een webapplicatie  gebruiken zodat de papierenpakjesbezorglijsten die de Pieten tijdens het bezorgen niet meer...   wegwaaien, nat worden, scheuren.  
Sinterklaas heeft met Wegwijspiet, Hoofdpiet de volgende eisen opgesteld zie **eisen** . 
Het is jouw opdracht om deze eisen om te zetten in een werkende webapplicatie die gehost is op GitHub pages.  

#### Opdracht 1  Database normaliseren
  
**1NF** 
	1.1 Schets 1NF  
	1.2 1NF uitwerken in een ERD
	1.3. Afbeelding 1NF
	
**2NF** 
		2.1. Schets 2NF 
		2.2 2NF uitwerken in een ERD
		2.3 Afbeelding 2NF
		
**3NF**
		3.1  Schets 3NF  
		3.2 3NF uitwerken in een ERD
	3.3 Afbeelding 3NF
	3.4 DDL bestand
	3.5 DML bestand mét 10 rijen dummy data 
	  
4 **Opdracht 2 Responive frontend ontwerp**
4.1 Framework zoals Bootstrap is oké. 	
4.2 Bonuspunten voor gevalideerde CSS en HTML5 (zie onder) frontend-ontwerp zonder framework. 
	4.3 Met gevalideerde HTML en CSS via https://validator.w3.org/ 
	4.4 Goede score via https://developers.google.com/speed/pagespeed/insights/?hl=nl   
4.5 Database is relationeel MySQL of NoSQL zoals Firebase of ... (?) 
4.6 Voorbeelden via printscreen is verplicht van de Pakjesboot12bezorgapp 

#### Opdracht 4 backend ontwikkelen 


**Webapplicatie eisen:**

 1. Voornaam 
 2. Achternaam  
 3. Een bezorgvolgnummer
 4. Straat en huisnummer 
 5. Postcode 
 6. Woonplaats 
 7. Sinterklaas en Hoofdpiet willen op elk moment via de smartphone een bezorgoverzicht met de onderstaande data inzien:  
 7.1 Straat en huisnummer, postcode,  Achternaam, Kado nummer, IsOnvoorzien, InSchoorSteenGestoptDoor, datum en tijdstip
 8. Het kado moet gemakelijk terug te vinden in de webaplicatie. 
  
 9. Verlanglijst met een limit van 10 kado's. De limiet kan je op twee manieren controleren. 
 10. InSchoorSteenGestoptDoor
 11. Onvoorzien (Denk; De pepernoten zijn op :smile: ...,  De schoorsteen is defect/verstopt...,  te glad dak...  )
 12. Bezorgtijd en bezorgdatum is tussen 4 en voor 5 december 08:00 uur CET.  
 13. De app wordt gebruikt met verschillende CRUD-rechten. Op basis van onderstaande emailadressen:  
Sinterklaas@sinterklaas.es,  
Hoofdpiet@sinterklaas.es, 
Wegwijspiet@sinterklaas.es 
 14. Een wachtwoord per gebruiker.
 15. Een herstelmanier om het wachtwoord te herstellen. Sinterklaas is moet nog wennen aan zijn smartphone dus da's een handige functie.   
 16. Bonuspunten voor een:  
	 16.1 Goede manier om het wachtwoord te beveiligen 
	 16.2 Toelichting van je keuze voor PHP, of Node.JS. 
	 16.3 Correcte 3NF
	 16.4 werkende DML en DDL
	 16.5. Reponcive CSS zonder Bootstrap of ander framework gebruik.  
	 16.6 Beschrijving van een of twee manieren om de ingevoerde data te valideren. 
 17. Is Javascript écht nodig voor .... of kan het ook met CSS3...?  
 18. Jezelf en je ouders kunnen op basis van het emailadres van je ouders **alleen** je verlanglijst aanmaken/indienen/bekijken. Geldt ook voor je je broer/zus. Niet van andere kinderen.

**CRUD-rechten** 	

| Naam   |CRUD-rechten  |
|--|--|
| Sinterklaas, HoofdPiet | CRUD  |
| Wegwijspiet, bezorgpieten  | R-U |
| Jezelf, je ouders* |  C-R |
| Bezorgpieten in opleiding |  R |


 



