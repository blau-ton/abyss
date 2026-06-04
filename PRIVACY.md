# Datenschutzerklärung — Anavara Abyss

**Stand:** Juni 2026
**Verantwortlich:** Anavara (Kontakt siehe [SUPPORT.md](./SUPPORT.md))

---

## Kurzfassung in einem Satz

**Anavara Abyss sammelt keine Daten über dich. Alles, was du in der App erfasst, bleibt auf deinem iPhone.**

---

## Welche Daten erhebt die App?

**Keine.**

Die App hat kein Backend, keinen Server, keinen Account und kein Analytics-System.
Es werden keine personenbezogenen Daten von uns erhoben, verarbeitet oder weitergegeben.

## Wo werden meine Tauchgangsdaten gespeichert?

Ausschließlich **lokal auf deinem iPhone**, im persönlichen Speicher der App
(SwiftData / Core Data). Du kannst sie jederzeit exportieren (CSV / UDDF) oder
durch Deinstallation der App komplett löschen.

Es gibt **keine** automatische iCloud-Synchronisation. Falls iCloud-Backup deines
iPhones aktiv ist, kann ein verschlüsseltes Backup der App-Daten auf deinem
iCloud-Konto entstehen — das ist Apple's iCloud-Backup-Mechanismus, nicht etwas,
das wir steuern oder einsehen können.

## Welche externen Dienste nutzt die App?

Genau einer: **Apple WeatherKit**.

- Zweck: Anzeige der aktuellen Lufttemperatur am letzten getauchten Spot
- Datenbasis: Koordinaten des letzten Tauchgangs (Breitengrad / Längengrad)
- Anbieter: Apple Inc.
- Datenschutz: WeatherKit wird von Apple selbst betrieben und ist Teil von iOS.
  Die Anfragen werden anonymisiert von Apple verarbeitet. Details:
  https://www.apple.com/legal/privacy/data/de/weather/

Wenn du diese Funktion nicht möchtest, kannst du Apps in iOS unter
**Einstellungen → Datenschutz & Sicherheit** den Zugriff auf Standortdienste
entziehen — die Wetter-Anzeige fällt dann einfach auf „–" zurück, der Rest der
App funktioniert weiter.

## Welche iOS-Berechtigungen fragt die App an?

- **Standort** *(„Bei Verwendung der App")* — nur damit du auf der Spots-Karte
  deine aktuelle Position siehst und Spots in der Nähe findest. Wird **nicht**
  übertragen.
- **Kamera** — ausschließlich für den QR-Code-Scan, um einen geteilten Tauchgang
  zwischen Buddies zu importieren. Kein Foto verlässt dein Gerät.
- **Fotomediathek-Schreibzugriff** — falls du exportierte Bilder (z.B. dein
  QR-Code) in deine Mediathek speichern möchtest.

Du kannst alle Berechtigungen in iOS unter
**Einstellungen → Anavara Abyss** jederzeit widerrufen.

## Tracking, Werbung, Analytics

**Nichts davon.** Die App enthält keine Tracking-SDKs, keine Werbe-IDs, kein
Crashlytics, kein Firebase, kein Mixpanel, kein gar nichts.

## Cookies

Die App ist kein Web-Service und setzt keine Cookies.

## Kontakt

Fragen, Anliegen oder Auskunftsersuchen nach DSGVO Art. 15: siehe
[SUPPORT.md](./SUPPORT.md).

## Änderungen

Wenn sich an dieser Erklärung etwas ändert, wird die neue Version in diesem
Repository veröffentlicht. Der Versionsstand oben markiert das aktuelle Datum.

---

## English (Summary)

**Anavara Abyss collects no data. Everything you log stays on your iPhone.**

The app has no backend, no account, no analytics. The only external service is
Apple WeatherKit (for showing the current air temperature at your last dive
spot), which is operated by Apple under their own privacy terms.

For the full text in English, please refer to the German version above (which is
authoritative) or contact us via [SUPPORT.md](./SUPPORT.md).
