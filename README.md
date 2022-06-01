Bei diesem GitHub Projekt handelt es sich um ein Blockly-Skript für ioBroker, um damit eine Gartenbewässerung zu steuern.

Funktionen:

- Automatische Bewässerung mit bis zu 6 Ventilen
- Entwickelt für HomeMatic (Adapter: hm-rpc), Sonoff (Adapter: sonoff) und Shelly (Adapter: shelly)
- Im Skript wird eine Anschaltzeit pro Aktorkanal gesetzt, damit die Aktoren automatisch ausschalten
- Die Ventile starten nacheinander
- Einzelne Ventile können deaktiviert werden
- Anzeige Gesamtlaufzeit, Restlaufzeit
- Anzeige Restlaufzeit gesamt / Restlaufzeit pro Ventil
- Anzeige Fortschritt gesamt in Prozent
- Anzeige Fortschritt pro Ventil in Prozent
- Benachrichtigung per Mail und/oder Pushover und/oder Telegram
- Benachrichtigung per Alexa Sprachausgabe
- Automatischer Start: Morgens, Abends (in Abhängigkeit vom Sonnenauf- und Untergang) oder 3 feste Startzeiten
- Intervall-Modus möglich
- Automatische Erstellung von Statistiken (Laufzeit / Wassermenge pro Woche, Monat, Jahr)
- Unterbrechung / Pausen-Funkton integriert

Hinweis zur Verwendung mit Tasmota
Mit Version 9.4.0 haben sich die Namen einiger Datenobjekte geändert. Daher funktioniert dieses Skript nur mit Tasmota Aktoren mit der Firmware 9.4.0 und neuer

