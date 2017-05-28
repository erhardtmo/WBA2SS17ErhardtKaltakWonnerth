# REST Modellierung

## Methoden:

- GET: Abfrage von Informationen (Read)
- POST: Erstellen von Informationen (Create)
- PUT: Aktualisieren von Informationen (Update)
- DELETE: Löschen von Informationen (Delete)


| Ressource | Methode | Semantik |
| ------------ | ------------ | ------------ |
| /meeting | POST | Erstellt ein Meeting und gibt die ID zurück |
| /meeting/{id} | PUT | Sendet Aktuelle Standort Information |
| /meeting/{id} | DELETE | Löscht das Meeting |
| /meeting/{id} | GET | Gibt die Aktuelle position |



