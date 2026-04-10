# Google Ads Kampagne – Microneedling | Da Eva Cosmetics

## Kampagnenstruktur

| Einstellung | Wert |
|---|---|
| **Kampagnentyp** | Search |
| **Ziel** | Conversions (Termin-Klick via studiobookr) |
| **Standort** | Kaufbeuren + 25 km Umkreis |
| **Sprache** | Deutsch |
| **Tagesbudget (Empfehlung)** | 15–25 € |
| **Gebotsstrategie** | Manuell CPC zum Start → nach 30 Conversions auf Ziel-CPA wechseln |
| **Anzeigenrotation** | Optimiert – bevorzugt leistungsstärkste Anzeigen |
| **Anzeigezeitplan** | Mo–Sa 08:00–20:00 Uhr |

---

## Ad Groups

### Ad Group 1 – „Microneedling" (High Intent)
> Nutzer suchen aktiv nach Microneedling-Behandlungen → höchste Kaufabsicht

**Keywords:**
```
[microneedling]
[microneedling kaufbeuren]
[microneedling thalhausen]
+microneedling +behandlung +kosmetik
"microneedling kosmetikstudio"
"microneedling professionell"
"microneedling gesicht"
```

**Negative Keywords (Kampagnenebene):**
```
-selber
-zuhause
-roller
-dermapen kaufen
-gerät
-kurs
-ausbildung
-jobs
-erfahrungen forum
```

---

### Ad Group 2 – „Anti-Aging" (Mid Intent)
> Nutzer suchen nach Anti-Aging-Lösungen, kennen Microneedling evtl. noch nicht

**Keywords:**
```
+faltenbehandlung +ohne +botox
+haut +straffen +behandlung
+anti +aging +kosmetik +behandlung
"kollagen behandlung gesicht"
"hyaluronsäure behandlung kosmetik"
"falten reduzieren ohne op"
"natürliches anti aging"
```

---

### Ad Group 3 – „Preis / Kosten" (Price Seekers)
> Nutzer vergleichen Preise → Angebotspreis prominent nutzen

**Keywords:**
```
[microneedling kosten]
[microneedling preis]
"microneedling was kostet"
+microneedling +preis +kosmetik
"microneedling wie viel kostet"
```

---

## Responsive Search Ad (RSA)

> Für jede Ad Group eine separate RSA verwenden. Headlines und Descriptions
> können pro Ad Group leicht variiert werden. Basis-RSA unten:

### 15 Headlines (max. 30 Zeichen je Headline)

| # | Headline | Zeichen |
|---|---|---|
| 1 | Microneedling ab 79 € | 22 |
| 2 | Jetzt Termin online sichern | 28 |
| 3 | Sichtbar jüngere Haut | 22 |
| 4 | Anti-Aging ohne Botox | 22 |
| 5 | BABOR Microneedling Experte | 27 |
| 6 | Kollagen-Boost Behandlung | 25 |
| 7 | Straffere Haut ab Sitzung 1 | 28 |
| 8 | Professionelles Microneedling | 30 |
| 9 | Falten natürlich reduzieren | 28 |
| 10 | Da Eva Cosmetics Kaufbeuren | 28 |
| 11 | Kosmetikstudio b. Kaufbeuren | 29 |
| 12 | Schmerzarme Anti-Aging Kur | 27 |
| 13 | Hyaluronsäure & Kollagen | 25 |
| 14 | Natürliches Lifting | 20 |
| 15 | Noch heute Termin verfügbar | 28 |

> **Pinning-Empfehlung:**
> - Position 1 (fest): „Microneedling ab 79 €" oder „Professionelles Microneedling"
> - Position 2 (fest): „Jetzt Termin online sichern" oder „Noch heute Termin verfügbar"
> - Position 3: frei rotieren lassen

### 4 Descriptions (max. 90 Zeichen je Description)

```
Description 1:
Professionelles Microneedling mit BABOR-Wirkstoffen. Sichtbar straffere Haut
bereits nach Behandlung 1 – Ersttermin jetzt ab 79 €. Termin sichern!

Description 2:
Natürliches Anti-Aging: Microneedling aktiviert Kollagen & Hyaluronsäure für
Ihre Haut. Keine OP, kein Botox. Ersttermin 79 € – jetzt online buchen!

Description 3:
Da Eva Cosmetics in Thalhausen bei Kaufbeuren. BABOR-zertifiziert.
Individuelle Beratung & schnelle Terminvergabe. Ersttermin ab 79 €!

Description 4:
Falten, schlaffe Haut oder Pigmentflecken? Microneedling – professionell,
schmerzarm & effektiv. Ersttermin 79 € – Termin jetzt vereinbaren!
```

---

## Ad Extensions (Anzeigenerweiterungen)

### Sitelink-Erweiterungen (4 Stück)
| Titel | Beschreibung | Ziel-URL |
|---|---|---|
| Über Da Eva | Ihr Kosmetikstudio in Thalhausen | /ueber-uns (Hauptwebsite) |
| Alle Behandlungen | Entdecken Sie unser Behandlungsangebot | /behandlungen |
| Preisliste | Transparente Preise für alle Treatments | /preise |
| Kontakt & Anfahrt | Adresse, Telefon & Öffnungszeiten | /kontakt |

### Callout-Erweiterungen
```
✔ BABOR Partner
✔ Schmerzarme Behandlung
✔ Individuelle Beratung
✔ Sofort-Termine verfügbar
✔ Ergebnis ab Sitzung 1
✔ Ohne OP & ohne Botox
```

### Call Extension
- Telefonnummer des Studios → TEL-NUMMER
- Nur während Öffnungszeiten aktiv schalten

### Location Extension
- Google My Business Profil verknüpfen
- Adresse: Da Eva Cosmetics, Thalhausen bei Kaufbeuren

### Preis-Erweiterung (optional)
```
Microneedling Ersttermin: ab 79 €
Microneedling 3er-Paket: ab 219 €
```

---

## Zielseite (Final URL)

Die Landingpage ist separat unter `/microneedling` oder als dedizierte WP-Seite erreichbar.
Alle Anzeigen zeigen direkt auf diese Seite (keine Weiterleitung auf die Startseite).

---

## Conversion Tracking

| Conversion-Aktion | Auslöser |
|---|---|
| Termin-Klick (primär) | Klick auf CTA-Button → studiobookr.com |
| Telefon-Klick | Klick auf Call Extension oder Tel.-Nr. auf LP |
| Scroll-Tiefe 75 % | Engagement-Signal (Secondary Conversion) |

**Empfehlung:** Google Tag Manager verwenden.
Trigger: Klick auf alle Elemente mit CSS-Klasse `.btn-primary` auf der Landingpage.

---

## Qualitätscheckliste vor Go-Live

- [ ] RSA Qualitätsbewertung ≥ „Gut" in Google Ads
- [ ] Final URL erreichbar und Seite lädt < 3 Sek. (PageSpeed)
- [ ] Conversion Tracking in Google Ads aktiv und testet korrekt
- [ ] Negative Keywords eingepflegt
- [ ] Anzeigezeitplan gesetzt (Mo–Sa 08–20 Uhr)
- [ ] Ad Extensions alle aktiviert
- [ ] DSGVO: Cookie-Banner auf Landingpage vorhanden
