# Projektstatus · NG-App

Stand: **01.11.2026**. Grundlage sind dokumentierte Projektstände und neuere Rückmeldungen des Projektinhabers. Keine neue Quellcode-, Geräte- oder Store-Prüfung durch diese Dokumentationsaktualisierung.

| Bereich | Belegter bzw. gemeldeter Stand | Grenze |
|---|---|---|
| Android-Auslieferung | VersionCode 37 war im internen Test; ein Update wurde nach erneuter Suche gefunden. Am 01.11. wurde VersionCode 38 als veröffentlicht gemeldet. | Interner Test, keine bestätigte Produktionsveröffentlichung; aktuelle Console und Paketprüfung ausstehend. |
| Kalender, Angebote, Prospekte, Einkaufsliste | Bestehende Projektbereiche mit laufenden Verbesserungen. | Vollständigkeit und Verhalten auf allen Geräten nicht abgenommen. |
| Anmeldung/Biometrie | Nach dem Update wurde erneut notwendige Methodenwahl sowie Fingerabdruckangebot statt gewünschter Gesichtserkennung gemeldet. | Offen; kein korrigierter Build nachgewiesen. Geräteunterstützung und vom Betriebssystem angebotene Methoden gesondert prüfen. |
| Kontoansicht | Übersichtlich gegliedertes Kontomenü statt unübersichtlicher grauer Kachelfläche angefordert. | Anforderung, keine abgeschlossene Umsetzung. |
| Scanner/Authenticator | In älteren Entwicklungsberichten vorhanden. | Import, Entsperren, Codeerzeugung und Anmeldung benötigen versionsbezogene Geräteabnahme. |

## Noch nachzuweisen

- Exakte Zuordnung des AAB zu VersionCode, sichtbarem Versionsnamen und Testveröffentlichung.
- Anmelden, erneutes Öffnen, Abbrechen und Fallback nach der Biometriekorrektur auf echten Geräten.
- Ladenauswahl ohne abgeschnittene Einträge, Blättern durch Prospekte und mehrere Einkaufsartikel ohne unerwünschten Listenwechsel.
- Regionale Angebotssuche, Push-Zustellung und verbleibende Scanner-/Authenticatorfälle.
- Updateverhalten auf mehreren Testgeräten, ohne Ergebnisse einer älteren Version ungeprüft zu übertragen.

Frühere offene Angaben zur Lieferung von VersionCode 38 sind durch die neuere Eigentümerrückmeldung ergänzt; die technische Paketprüfung bleibt davon getrennt.
