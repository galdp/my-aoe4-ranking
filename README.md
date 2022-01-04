# My Ao4 Ranking

# Usecases 

Benutzer will sich anmelden, damit er sehen kann was für Ranking und Elo der Nutzer hat.

Benutzer will eingeloggt bleiben, damit er beim nächsten Start der App eingeloggt bleibt.

Benutzer will sich ausloggen, damit er sich ggf. erneut anmelden kann.

Benutzer will Freunde hinzufügen, damit er sehen kann, was für ein Ranking oder Elo der Freund hat.

Benutzer will den aktuellen Screen neuladen, damit er die aktuellsten Daten hat.

# Screen Login

* Logo oder Bild
* Eingabefeld mit Benutzername als Label
* Button mit Login


# Screen Ranking

* Benutzername
* Stats
  * 1v1
    * rank 
    * elo
    * winPercent
    * wins
    * losses
    * total
    * winStreak
  * 2v2
  * 3v3
  * 4v4
* Pull to refresh / Refresh button (reload?)

# API

* https://api.ageofempires.com/api/ageiv/Leaderboard
  * Header "Accept: application/json"
  * Content-Type "application/json"
  * Body: {"region":"7","versus":"players","matchType":"unranked","teamSize":"1v1","searchPlayer":"crazyba2na","page":1,"count":1}

Quelle https://www.ageofempires.com/stats/ageiv/