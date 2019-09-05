# Profil-Seite

![layout](drafts/page.png "Portfolio Seite")

- Seite nur für mobile
- meta Tag für die korrekte Skalierung auf Handys benutzen:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1">
  ```
- Link für Email, der E-Mail Anwendung öffnet (0/5)
- Link für Telefon, der Telefon-Anwendung öffnet (0/5)
- Link zum Lebenslauf(PDF), der einen Download auslöst (0/5)
- Links zu Social Media Profilen
  - Haben Icons der Dienste (1/10)
  ```diff
  - Die Icon-Klassen sind da, aber es werden keine Icons geladen weil das css von Fontawesome nicht integriert wurde
  ```
  - Sollen in einem neuen Tab öffnen (0/5)
  
- Foto, das im Kreis dargestellt wird, mit border-radius (5/5)
- Navigation zu den Abschnitten mit Hash-Links (10/10)
- Bilder im Portfolio sollen verlinkt sein (0/10)

## Anforderungen für den Code
- Keine Block-Tags in Inline-Tags (10/10)
- Padding in den Links der Hauptnavigation (10/10)
- Abstand zwischen Text und Fensterrand und zwischen Text und Element-Rand (10/10)
- Korrekte html-Grundstruktur (html, head, body) (5/10)
```diff
- Es gibt tags, die nicht geschlossen sind. Z.B. span in Zeile 31
- Bitte keine inline-styles benutzen. Das kann man einfacher in der CSS-Datei definieren.
```
- Keine Viewport-Elemente im head (5/5)

### Punkte
(**56**/100)
