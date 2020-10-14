# Java 

## Pokedex

Implementiere einen kleinen Pokedex. 
Als Datenquelle dient uns dieses Google Sheet: 
https://docs.google.com/spreadsheets/d/1usj3ljVk3gElCo8NTVhv3gczC3HBveIzypEmrPGBPEY/edit#gid=1526907300

## Lookup 

Über die Konsole soll der User entweder die Indexnummer oder den Namen eines Pokemons eingeben. 
Wird kein Pokemon gefunden mit der Indexnummer oder dem Namen, wird eine Fehlermeldung ausgegeben.
Wird es gefunden, dann werden einige Daten auf der Konsole ausgegeben und die ASCII Repräsentation falls sie im ordner ascii-art existiert. 

### Repräsentation 

Zu Beginn des Kampfs, werden dem Spieler die Stats seines Pokémons ausgegeben. 
Das könnte z.B so aussehen: 

```
Bulbasaur (100 ♥ | 49 ⚔️ | 49 🛡️)                
(1) Overgrow                                    
(2) Chlorophyll                                   
```

Bulbasaur ist dabei der Name des Pokémons. 100 ist die maximale Gesundheit (HP google sheet). 49 die Attacke (attack google sheet) und die anderen 49 neben dem Schild die Verteidigung (defense google sheet).
Overgrow und Chlorophyll sind dabei die beiden möglichen Attacken (abilities). 
Ist ein Pokémon legendär (is_legendary) solltest du einen ⭐ vor dem Pokémon Namen angeben. 
