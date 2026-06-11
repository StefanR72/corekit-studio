# CoreKit Studio Webseite

Statische GitHub-Pages-Webseite fuer CoreKit Studio.

Geplante Domain: `corekit-studio.de`

Geplante Mailadressen:

- `support@corekit-studio.de`
- `privacy@corekit-studio.de`
- `legal@corekit-studio.de`

GitHub-Pages-Custom-Domain:

- `corekit-studio.de`
- `www.corekit-studio.de` sollte per DNS-CNAME auf die GitHub-Pages-Adresse zeigen.

## Vor der Veroeffentlichung ersetzen

- `APP NAME 1`, `APP NAME 2`, `APP NAME 3` durch deine Apps
- `DEIN RECHTLICHER NAME ODER FIRMENNAME`
- `GESCHAEFTSADRESSE`, `PLZ ORT`
- App-Beschreibungen und Plattformen

## Empfohlener Ablauf

1. Domain `corekit-studio.de` beim Registrar final auf Verfuegbarkeit pruefen und kaufen.
2. Mailadressen einrichten: `support@corekit-studio.de`, `privacy@corekit-studio.de`, `legal@corekit-studio.de`.
3. Geschaeftsadresse klaeren: Virtual Office, Coworking-Adresse oder Impressumsservice.
4. Apple Developer Account pruefen: Individual oder Organisation.
5. App Store Connect DSA-Kontaktdaten mit der neuen geschaeftlichen Adresse und Mail pflegen.
6. Webseite auf GitHub Pages veroeffentlichen.
7. In GitHub Pages `corekit-studio.de` als Custom Domain setzen.
8. Bei STRATO die GitHub-Pages-DNS-Eintraege setzen.

## GitHub Pages

Wenn das Repository auf GitHub liegt:

1. Repository oeffnen.
2. `Settings` -> `Pages`.
3. Source: `Deploy from a branch`.
4. Branch: `main`, Folder: `/root`.
5. Speichern.

Danach ist die Seite unter der GitHub-Pages-Adresse erreichbar.

## DNS fuer GitHub Pages

Fuer `corekit-studio.de`:

- A `@` -> `185.199.108.153`
- A `@` -> `185.199.109.153`
- A `@` -> `185.199.110.153`
- A `@` -> `185.199.111.153`

Optional fuer IPv6:

- AAAA `@` -> `2606:50c0:8000::153`
- AAAA `@` -> `2606:50c0:8001::153`
- AAAA `@` -> `2606:50c0:8002::153`
- AAAA `@` -> `2606:50c0:8003::153`

Fuer `www.corekit-studio.de`:

- CNAME `www` -> `<github-benutzername>.github.io`

Wichtig: Die GitHub-Pages-Adresse ohne Repository-Namen verwenden.

## Hinweis

Die Platzhalter sind bewusst sichtbar. Vor einer oeffentlichen Nutzung sollten Impressum,
Datenschutzerklaerung und Apple-Kontaktdaten rechtlich geprueft werden.
