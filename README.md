# jsd24-Databaser-25yhp-Grupp-Examination-SQL-bulletin
Grupp examination: SQL med PostgreSQL

# Grupp examination: SQL med PostgreSQL - SQL bulletin

## Instruktioner

Ni ska i denna examination bygga ett API för en tjänst som fungerar som en anslagstavla. En användare kan posta ett meddelande till en kanal som denna "prenumererar" på samt se andra meddelanden som finns i den kanalen. Tänk typ väldigt enkla Facebook grupper.

* En användare kan "prenumerera" på ingen eller flera olika kanaler.
* En användare kan posta ett meddelande till enbart en kanal. Kan dock bara posta ett meddelande till en kanal som användaren "prenumererar" på.
* En användare kan äga inga eller flera kanaler.
* Ett meddelande kan tillhöra enbart en kanal (**Ej Guldstjärna**)
* Ett meddelande kan enbart komma från en användare.
* En kanal kan ha inga eller flera meddelanden.
* En kanal kan enbart ha en ägare.


Läs igen noga ovan och därför modellera upp databasen med dess entiteter och relationer i ett ER-diagram. Därefter bygg databasen och API:et.

**Hur noga ni vill vara med API:et får ni själva välja så länge det fungerar enligt kraven ovan. Exempelvis är det inget krav på att validera någon data från frontend eller använda sig av JSON Web token för att skapa en inloggningssession.**

## Betygskriterier

**För Godkänt:**
* Har ett komplett ER-diagram med alla entiteter och relationer som täcker in kraven ovan.
* Uppfyller all funktionalitet.
* Att alla gruppmedlemmar deltar eller meddelar frånvaro till gruppen senast 12 timmar innan möten, detta gäller för alla grupplanerade möte.
* Alla gruppmedlemmar deltar i redovisnings momentet (alla ska prata ungefär lika mycket).
* bifoga exempelanrop (använd till exempel: Postman) till alla endpoints (se länk under inlämning)

**För Guldstjärna:**
* Ett meddelande kan tillhöra en eller flera kanaler.
* Det går att sortera meddelanden på datum.
* Exempelanrop bifogas (Postman).

## Handledning

Tid för handledning bokar ni via handledningsdokumentet: https://docs.google.com/document/d/1zCTCEAbQNIL1zewBV5dzRnqaI0bfOLQJ7r1JBxFD0zg/edit?usp=sharing


## Inlämning

Inlämning sker på Azomo med en länk (alla i gruppen måste göra en inlämning) till ert Github repo med er kod senast **22/5 22:59**.
[dokumentation för att importera/exportera data till postman](https://learning.postman.com/docs/getting-started/importing-and-exporting/importing-and-exporting-overview/#importing-data-into-postman)

### Redovisning
Sker genom att alla grupper redovisar under lektionstiden den 21/5. MAX 20 min redovisning/presentation.
