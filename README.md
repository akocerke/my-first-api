# my-first-api
 testen wie sau 🤣👍
# Memo an mich
GET: Abrufen von Informationen, z.B. alle Elemente in der Liste
PUT: Aktualisieren eines vorhandenen Elements
POST: Hinzufügen eines neuen Elements

## Allgemeine Infrastruktur
![](./images/Infrastructure.png)

## API Dokumentation
`GET /allitems`: Gibt Alle Elemente der Shopping-Liste zurück

`GET /itembyid/{itemdId}`: Gibt ein einzelnes Elemnt zurück.
**Parameter**: `itemId` - Einzigartige Id des Elements

### Erstellen von einem neuen Element
`POST /additem`: Hinzufügen eines neuen Elements in die Shopping-Liste
**Parameter**:  `name`: Der Name des Elements
                `menge`: Die Menge des Elements
                `einheit`: Die Einheit des Elements(Stück, Kilogramm, Liter...)

### Löschen von einem Element
`DELETE /deleteitem/{itemId}`: Löscht ein Element aus der Shopping-Liste
**Parameter**:  `itemId`: Die eindeutige ID des zu löschenden Elements

### Aktualisieren von einem Element
`PUT /updateitem/{itemId}`: Aktualisiert ein vorhandenes Element in der Shopping-Liste
**Parameter**:  `itemId`: Die eindeutige ID des zu aktualisierenden Elements

