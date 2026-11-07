# Memolumen

Der Name verbindet die lateinischen Wörter *memoria* (Erinnerung) und *lumen* (Licht): Memolumen bringt deine Erinnerungen zum Leuchten.

Memolumen macht aus einem Windows-Tablet einen digitalen Bilderrahmen. Die App zeigt Fotos und Videos als Diashow im Vollbild, blendet Uhr und Kalender ein und wird bequem über eine Weboberfläche vom Handy, Tablet oder PC im Heimnetz verwaltet. Auf Wunsch arbeitet Memolumen mit Home Assistant zusammen.

In diesem Repository stehen die Installer von Memolumen unter [Releases](https://github.com/rolhan95/memolumen-releases/releases) zum Download bereit. Memolumen holt sich neue Versionen von hier auch selbst über sein Online-Update.

## Was Memolumen kann

### Diashow
- Fotos mit Übergängen, unscharfem Hintergrund hinter Hochkant-Fotos und einem Sparmodus für ältere Tablets
- Videos (MP4, WebM, MOV) zwischen den Fotos, mit oder ohne Ton; iPhone-Videos im HEVC-Format (auch HDR) werden automatisch in ein abspielbares Format umgerechnet
- iPhone-Fotos im HEIC-Format werden automatisch umgewandelt
- Antippen öffnet ein Menü: vor und zurück, Pause, Helligkeit, Bildschirm aus, Einstellungen

### Fotoquellen
- Hochladen über die Weboberfläche
- Geteilte Alben aus Apple iCloud und Google Fotos, die automatisch abgeglichen werden
- Netzwerkordner auf einem NAS (SMB), auch mit Unterordnern

### Uhr, Kalender und Feiertage
- Digitale oder analoge Uhr, Kalender als Monatsblatt und Terminliste
- Termine aus Kalender-Abos (ICS, z. B. Google Kalender), inklusive Serienterminen
- Antippen des Kalenders zeigt die Termine der nächsten Tage
- Feiertage für Deutschland (alle Bundesländer), Österreich und die Schweiz

### Weboberfläche
- Verwaltung aller Einstellungen vom Handy oder PC, geschützt mit PIN oder Passwort und über HTTPS
- Ersteinrichtung mit Assistent: einfach den QR-Code am Rahmen scannen
- Datensicherung der Einstellungen mit automatischen Sicherungsständen
- Deutsch und Englisch
- Mitinstalliertes Benutzerhandbuch

### Home Assistant
- Automatische Einbindung über MQTT: Bildschirm, Helligkeit, Umgebungslicht, Abwesenheitsmodus und weitere Entitäten
- Steuerung über eine REST-Schnittstelle mit API-Token
- Türklingel: Einblendung des Live-Bilds einer Kamera am Rahmen
- Eigene Integration für HACS: [rolhan95/memolumen-homeassistant](https://github.com/rolhan95/memolumen-homeassistant)

### Online-Update
- Memolumen sucht selbst nach neuen Versionen, zeigt die Neuerungen an und installiert sie auf Knopfdruck oder nachts automatisch
- Jeder Installer wird vor der Installation anhand seiner SHA-256-Prüfsumme geprüft
