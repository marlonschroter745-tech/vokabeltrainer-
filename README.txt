VOKA – DEIN VOKABELTRAINER

Dateien im Projekt:
- index.html: App-Oberfläche und Logik
- sw.js: Service Worker für das Zwischenspeichern der App-Dateien und Offline-Start nach dem ersten Laden

GITHUB PAGES – KURZANLEITUNG
1. Erstelle ein GitHub-Repository namens vokabeltrainer.
2. Lade index.html und sw.js in den Hauptordner (Root) des Repositorys hoch.
3. Öffne Settings > Pages.
4. Unter Build and deployment wähle Deploy from a branch.
5. Wähle Branch main und Folder /(root), dann Save.
6. Warte, bis GitHub Pages veröffentlicht hat. Die Adresse erscheint in Settings > Pages.
7. Öffne die Adresse in Safari und lade sie einmal vollständig, während du online bist. Danach kann der Service Worker die App-Dateien für Offline-Aufrufe zwischenspeichern.

DATENSCHUTZ UND SPEICHERUNG
Vokabeln und Lernstände werden im localStorage des verwendeten Browsers gespeichert. Sie werden nicht an GitHub übertragen. GitHub hostet nur die App-Dateien. Lösche keine Website-Daten, wenn du deine lokalen Vokabeln behalten willst. Exportiere regelmäßig über „Sicherung exportieren“ eine JSON-Datei.

WICHTIGER HINWEIS
Diese erste Version unterstützt den Import von Text/CSV und von Voka-JSON-Sicherungen. Excel kann man zunächst als CSV speichern. PDF-/Word-/Foto-OCR-Import, Bulk-Bearbeitung, echte lokale KI, vollständig frei anpassbare Startseite/Navigationsanordnung und weitere Details sind noch nicht vollständig umgesetzt. Die Grammatik-Hilfe ist ein kleines Offline-Nachschlagewerk mit Stichwortantworten, keine echte generative KI.
