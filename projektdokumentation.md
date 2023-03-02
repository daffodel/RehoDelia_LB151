# Projekt-Dokumentation

Reho

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 17.02 | 0.0.1   | Versuch des Aufstellen einer Login Page                      |
| 23.02 | 0.0.2   | Erster Versuch erstellen des eigentlichen Spieles            |
| 25.02 | 0.0.3   | Wieder von neu angefangen, wegen nicht behebbaren Fehlern    |
| 28.02 | 0.0.4   | Startpage mit Namenseingabe, versucht Spiel aufzusetzen      |
| 01.03 | 0.0.4   | Versucht das Spiel zu programmieren, wieder die selben Fehler|
| 02.03 | 0.0.4   | Versucht Fehler zu beheben                                   |

# 0 Ihr Projekt

Mein Projekt ist eine Webapplikation zu programmieren, bei der man ein Quiz durchspielen kann.

# 1 Analyse

* Tier 1 (Presentation): Startseite mit Eingabe für den Namen der Spieler, Admin-Login, Spiel Seite, Highscore Liste, Hinzüfugen einer Wörter oder Phrase Liste, Bearbeiten einer Wörter oder Phrase Liste
* Tier 2 (Webserver): Anzeige und Steuerung des GUIs
* Tier 3 (Application Server): liest Inhalt aus der Datenbank aus, schreibt Daten in die Datenbank, beinhaltet die Logik des Projekts
* Tier 4 (Dataserver):Speichert die Login-Daten, den Namen des Spielers und die Highscore-Daten, beinhaltet eine Liste von W

# 2 Technologie

* Tier 1 (Presentation): JSF, PrimeFaces, CSS
* Tier 2 (Webserver): JSF, GlassFish
* Tier 3 (Application Server): Java
* Tier 4 (Dataserver): MySQL, JDBC

# 3 Datenbank

Ich benutze MySQL für meine Datenbank und benutze JDBC als Schnittstelle.

# 4.1 User Stories

| US-№ | Verbindlichkeit | Typ            | Beschreibung                                                                                                         |
| ---- | --------------- | ---------------| ---------------------------------------------------------------------------------------------------------------------|
| 1    | Muss            | Funktionalität | Als ein Administator möchte ich mich durch Passwort und Benutzername authentifizieren, damit ich mich einloggen kann.|
| 2    | Muss            | Funktionalität | Als ein Administrator möchte ich Phrasen und Rätselwörter anlegen, ändern und löschen können, damit es genug Rätselwörter gibt und dass es keine Fehler gibt.|
| 3    | Muss            | Funktionalität | Als ein Administrator möchte ich Kategorien anlegen und zuteilen können, damit alles übersichtlich eingeteilt ist.|
| 4    | Muss            | Funktionalität | Als ein Administrator möchte ich einzelne Einträge der Highscore-Liste löschen, damit falsche Einträge entfernt werden können|
| 5    | Muss            | Funktionalität | Als ein Kandidat möchte ich meinen Namen eingeben könne, damit er auf der Highscore Liste erscheinen kann.|
| 6    | Muss            | Funktionalität | Als Kandidat möchte ich zu jeder Zeit meinen Kontostand sehen, damit ich weiss wie viel Geld ich übrig habe|
| 7    | Muss            | Funktionalität | Als ein Kandidat möchte ich zu jeder Zeit die Lebenspunkte sehen können, damit ich weiss wie viele Versuche ich übrig habe|

✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc. oder Zahl), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). 

# 4.2 Testfälle

| TC-№ | Vorbereitung | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |              |         |                   |
| ...  |              |         |                   |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

# 5 Prototyp

✍️ Erstellen Sie Prototypen für das GUI (Admin-Interface und Quiz-Seite).

Admin Interface:
![adminview](https://user-images.githubusercontent.com/107002802/222438123-31632b6d-7624-4b04-88ed-fcbc4f6c1402.png)

Quiz-Seite:
![gameview](https://user-images.githubusercontent.com/107002802/222443000-026c448e-a86f-4b04-81f3-6023c26b8ee0.png)



# 6 Implementation

✍️ Halten Sie fest, wann Sie welche User Story bearbeitet haben

| User Story | Datum | Beschreibung                             |
| ---------- | ----- | -----------------------------------------|
| 1          | 17.02 |  Versucht, jedoch gescheitert            |
| 5          | 28.02 |  Wird nicht in die Datenbank eingetragen |
| 6          | 01.03 |  Versucht, jedoch gescheitert            |
| 7          | 01.03 |  Versucht, jedoch gescheitert            |


# 7 Projektdokumentation

| US-№ | Erledigt? | Entsprechende Code-Dateien oder Erklärung |
| ---- | --------- | ----------------------------------------- |
| 1    | nein      |                                           |
| 2    | nein      |                                           |
| 3    | nein      |                                           |
| 4    | nein      |                                           |
| 5    | ja        | index.html                                |
| 6    | nein      |                                           |
| 7    | nein      |                                           |


# 8 Testprotokoll

✍️ Fügen Sie hier den Link zu dem Video ein, welches den Testdurchlauf dokumentiert.

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

# 9 `README.md`

✍️ Beschreiben Sie ausführlich in einer README.md, wie Ihre Applikation gestartet und ausgeführt wird. Legen Sie eine geeignete Möglichkeit (Skript, Export, …) bei, Ihre Datenbank wiederherzustellen.

# 10 Allgemeines

- [ ] Ich habe die Rechtschreibung überprüft
- [ ] Ich habe überprüft, dass die Nummerierung von Testfällen und User Stories übereinstimmen
- [ ] Ich habe alle mit ✍️ markierten Teile ersetzt
