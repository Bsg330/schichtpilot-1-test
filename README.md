# SchichtPilot 1.0 Beta – neuer Prototyp

Separate Neuimplementierung. Auf eigenem GitHub-Pages-Pfad hosten, nicht die alte Beta überschreiben. Nach erstem vollständigen Laden offline nutzbar (Service Worker benötigt HTTPS). Daten im Browser lokal gespeichert. Regelmäßig JSON-Sicherung erstellen.

Funktionen: Dashboard, Kalender, Früh/Spät/Nacht, Mehrtageseingabe per Anzahl, Urlaub, Brutto-Grundvergütung, frei einstellbare pauschale Nacht-/Sonntagszuschläge, grobe Netto-Prognose mit konfigurierbarem Abzug, Druckdialog/PDF, Sicherungs-Export/Import. Reisebanner als Platzhalter; keine Werbenetzwerk-Anbindung.

**Noch nicht enthalten:** gesetzlich genaue deutsche Nettolohnberechnung, Feiertagskalender, exakte zeitsegmentbasierte Zuschlagsberechnung, Alt-Beta-Importkonverter, Monatsgehalt, vollständige Offline-PDF-Erzeugung ohne Druckdialog, echte Reiseangebote. Zuschläge werden in dieser Beta pauschal nach Schichttyp bzw. Sonntag des Startdatums berechnet. Keine automatische steuerfreie Behandlung. Nicht als Lohnabrechnung verwenden.


Feiertags-Update: Bundesland, örtliche Sonderfeiertage, individuell einstellbarer Feiertagszuschlag; Schichten über Mitternacht anteilig. Bestehende Daten bleiben unter demselben localStorage-Schlüssel.


## Beta 1.0 – Schicht-Designer
Eigene Schichtarten mit Farbe, Symbol und Zeiten; Kalender-/Listenumschaltung; Hamburger-Menü; Nachtzuschlag nach Uhrzeit 20–06; Sondertage 24./31.12. ab 14 Uhr als konfigurierbarer Feiertagszuschlag. Die Abrechnung ist weiterhin eine vereinfachte Prognose.
