GlobalContainer – Dein Platz im Container, einfach reserviert.
Dein Paket für einen kleinen Preis.

Mit GlobalContainer kannst du erstmals einfach und bequem aus Deutschland, Frankreich, Belgien und England Containerplatz für den Versand nach Afrika – z. B. nach Luanda (Angola) – oder in die andere Richtung reservieren.

Deine Vorteile auf einen Blick:

🔍 Container finden: Verfügbare Container einsehen und direkt reservieren
💬 Chatfunktion: Kommuniziere direkt mit anderen Nutzern
🧾 Inserate & Gesuche: Erstelle Inserate oder Gesuche, verwalte, bearbeite oder lösche sie jederzeit
⭐ Watchlist: Merke dir interessante Inserate und Gesuche
🧑‍💼 Profil: Erstelle dein eigenes Nutzerprofil
💳 Zahlung (coming soon): Bald kannst du direkt über die App bezahlen
GlobalContainer bringt Menschen zusammen, die Dinge über Kontinente hinweg teilen, versenden oder transportieren möchten – ganz einfach über dein Smartphone.

## Geplantes Design

<p>
  <img src="./img/HauptscreenOffer.png" width="200">
  <img src="./img/HauptscreenRequest.png" width="200">
  <img src="./img/DetailScreen.png" width="200">
  <img src="./img/WatchlistRequest.png" width="200">
  <img src="./img/Profil.png" width="200">
</p>

## Features

 ##### Willkommens-/Einführungsscreen 
    * Einführung in die App und ihre Funktionen.
    
##### Registrierung/Login
    * Registrierung
    * Login
    * Passwort zurücksetzen
    
##### Containerübersicht Angebot
    * Übersicht über verfügbare Container, aktuelle Reservierungen und Benachrichtigungen.
    
##### Containerübersicht Anfrage
    * Liste der verfügbaren Container mit Details zu Zielort und Abfahrtsdatum.
    * Such- und Filteroptionen.
    
##### Merkliste Angebote
    * Die Speicherung von Container-Angebote anderer Nutzer, die für den Benutzer
      später interessant sein könnten, ermöglicht es, relevante Informationen zu speichern
      und bei Bedarf darauf zurückzugreifen.
    
##### Merkliste Anfragen
    * Die Speicherung von Container-Anfragen anderer Nutzer, die für den Benutzer
      später interessant sein könnten, ermöglicht es, relevante Informationen zu speichern
      und bei Bedarf darauf zurückzugreifen.
    
##### Filter Angebebot und Anfragen
    * Die Filterung von Containerangeboten und Anfragen nach Städten, Zeit und Kubikmetern hilft,
      Zeit bei der Suche zu sparen und gezielt den passenden Container zu finden.
    
##### Profil
    * Profilansicht und -bearbeitung.
  
    
#### Projektaufbau
Die Architektur des Projekts basiert auf dem Model-View-ViewModel (MVVM) Muster mit der Verwendung von Repositories für die Datenverwaltung. 

#### Datenspeicherung
Sobald der Nutzer eine Aktion ausführen möchte, muss er sich anmelden oder einloggen. Dies erfolgt über Firebase Authentication.
Der Nutzer hat die Möglichkeit, Daten im Firestore zu speichern und zu filtern.

#### API Calls
[APIs](https://ship.freightos.com/api/shippingCalculator)

#### 3rd-Party Frameworks
Firebase, Firestore

## Ausblick
Nach dem PraxisProjekt möchte ich in der App eine Zahlungssytem implementieren (Paypal,Lastschrift), Bewertungssystem der Transaktionen und die App veröffentlichen.

 
 
