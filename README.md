# BORDFUNK – Sprachsteuerung für Star Citizen

**Deine Crew hört mit.** Du sagst „Flugbereit“, „Schilde auf Maximum“ oder „Gunnar, Feuer frei“, und BORDFUNK drückt die passenden Tasten in Star Citizen. Zwei Crewmitglieder antworten mit eigener Stimme. Alles läuft **komplett offline**, ohne Konto, ohne Cloud und ohne Abo.

> **Demo:** Die Demo kann alles, hört aber pro Programmstart 30 Minuten lang zu. Danach einfach neu starten.
> **[⬇ Demo herunterladen](../../releases/latest)**

![Cockpit](bilder/cockpit.png)

## Was BORDFUNK kann

- **Deine Crew:** **Freya** ist der Bordcomputer für Navigation, Schiff und Meldungen. **Gunnar** ist der taktische Co-Pilot für Waffen, Ziele und Verteidigung. Beide haben eine eigene, natürlich klingende Stimme mit Funk-Klang. Sprich sie mit Namen an, oder sag einfach den Befehl.
- **Versteht freie Sätze:** „Mach bitte das Licht an“, „Mehr Strom für die Waffen“, „Fahrwerk raus und Licht an“. Füllwörter und Reihenfolge sind egal.
- **Deine eigenen Tasten:** BORDFUNK liest die Tastenbelegung direkt aus deinem Star Citizen. Belegst du im Spiel etwas um, wird das sofort übernommen, auch nach Patches.
- **Mitwachsend:** Neue Spielfunktionen aus Patches bekommen automatisch einen Sprachbefehl.
- **Spielmeldungen:** Freya sagt Schutzzonen, Landefreigabe, Quantensprung-Ankunft und Warnungen in eigenen Worten an.
- **Sicher:**
  - Gehaltene Tasten werden immer losgelassen, auch wenn du das Spielfenster verlässt.
  - Notausstieg und Schleudersitz laufen erst nach „bestätigt“.
  - „Feuer“ allein feuert nie.
- **Startet mit dem Spiel:** Auf Wunsch startet BORDFUNK automatisch, sobald Star Citizen läuft, und beendet sich danach.
- **Über 110 Befehle:** Flug, Energie, Schilde, Waffen, Ziele, Gegenmaßnahmen, Landung, Docking, Abläufe wie „Klar zum Start“ und Werkzeuge wie Uhrzeit oder Timer.

## Schnellstart

1. Die neueste ZIP-Datei unter **[Releases](../../releases/latest)** herunterladen und entpacken.
2. `Bordfunk.exe` starten.
   Erscheint „Der Computer wurde durch Windows geschützt“: auf **Weitere Informationen → Trotzdem ausführen** klicken.
3. Unter **Einstellungen → Spracheingabe** eine Push-to-Talk-Taste festlegen.
4. Im Spiel die Taste halten und sprechen. Ein paar Beispiele:

| Sag … | BORDFUNK macht |
|---|---|
| „Flugbereit“ | Systeme hochfahren |
| „Landeerlaubnis“ | Landung anfragen |
| „Fahrwerk ausfahren“ | Fahrwerk |
| „Schilde auf Maximum“ | Energie auf die Schilde |
| „Gunnar, Feuer frei“ / „Feuer einstellen“ | Dauerfeuer an und aus |
| „Ausweichen“ | Täuschkörper und Störsender |
| „Quantensprung“ | Quantensprung auslösen |
| „Frea, wie spät ist es?“ | Freya sagt die Uhrzeit |

Alle Befehle stehen im Programm unter **Befehle**.

## Voraussetzungen

- Windows 10 oder 11 (64 Bit)
- Mikrofon oder Headset
- Etwa 500 MB freier Speicher
- Star Citizen (für die Tasten aus dem Spiel; ohne Spiel gelten die Standardtasten)

## Häufige Fragen

**Verändert BORDFUNK das Spiel?** Nein. Es liest die Tastenbelegung nur und sendet ganz normale Tastendrücke, wie eine Tastatur. Spieldateien werden nicht verändert.

**Braucht es Internet?** Nein. Spracherkennung und Stimmen laufen auf deinem PC.

**Welche Sprache?** Deutsch. Weitere Sprachen sind in Arbeit.

**Wie entferne ich die Demo?** Falls eingeschaltet, zuerst „Mit dem Spiel starten“ ausschalten, dann den Ordner löschen. Sonst wird nichts installiert.

## Unterstützen

Wenn dir BORDFUNK gefällt, freue ich mich über eine kleine Spende über den **♥ Sponsor**-Knopf oben auf der Seite. Damit kann ich BORDFUNK weiterentwickeln: mehr Sprachen, mehr Spiele, neue Stimmen.

## Lizenzen und Hinweise

- BORDFUNK ist ein inoffizielles Fan-Projekt und steht in keiner Verbindung zu Cloud Imperium Games. Star Citizen® ist eine Marke von Cloud Imperium Rights LLC.
- Die verwendeten Bestandteile und ihre Lizenzen stehen im Programmordner unter `lizenzen\`.
- Das Sprachmodul nutzt Piper und eSpeak NG (GPL-3.0). Sein Quelltext liegt unter `quelltext\`.

---

### English

**BORDFUNK** is an offline voice-control tool for Star Citizen with a virtual two-person crew. It currently understands **German** voice commands. It reads your in-game keybindings, presses the keys for you and announces game events. No account, no cloud. The demo has all features and listens for 30 minutes per start. Unofficial fan project, not affiliated with Cloud Imperium Games.
