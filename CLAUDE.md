# chroma.digital — Projektkontext

## Wer bin ich?
Sebastian Schlunk, UX-Designer, selbständig.
Kontakt: mail@chroma.digital

## Was ist dieses Repo?
Landingpage für mein BFSG-Compliance-Angebot an Online-Shop-Betreiber.
Zielgruppe: deutscher Mittelstand, Fokus Möbel & Sanitär, E-Commerce allgemein.

## Hosting & Domains
- **Repo:** https://github.com/seppsan09/chroma-digital
- **Live (Vercel):** https://chroma-digital.vercel.app/
- **Geplante Domain:** chroma.digital (registriert bei United Domains)
- **E-Mail:** mail@chroma.digital (bereits eingerichtet)

## Tech-Stack
- Statisches HTML/CSS, kein Framework
- Deployed via Vercel (Auto-Deploy bei Push auf main)

## Angebot (aktuelle Paketierung)
- Kostenloser Report: Sales-Türöffner, kein Preis
- Compliance Report: 890€ (vollständiger Befund inkl. manueller Tests)
- Umsetzungs-Roadmap: ab 2.900€ (inkl. 100 Tickets, +25€/Ticket)
- Begleitung: 150€/h (optional, kein eigenständiges Paket)

## Zusammenhang mit AccessibilityScout
Das Accessibility-Repo (https://github.com/seppsan09/Accessibility) enthält das interne
Crawler-/Audit-Tool. Die Landingpage hier ist das öffentliche Gesicht.

---

## OFFENE TODOS

### TODO: Landingpage — Pakete aktualisieren
- Aktuelle Seite zeigt noch alte Paketierung
- Neu: Compliance Report 890€, Umsetzungs-Roadmap ab 2.900€
- Roadmap-Preismodell transparent erklären: "2.900€ inkl. 100 Tickets, jedes weitere 25€"
- Beispielrechnung zeigen: "Typischer Shop: 80–120 Tickets. Bei 100: 2.900€. Bei 150: 4.150€."
- Begleitung 150€/h als optionalen Zusatz, nicht als gleichwertiges drittes Paket

### TODO: Self-Service-Formular
- Formular auf der Landingpage: Name, E-Mail, Firma, Shop-URL
- CTA: "Kostenlos prüfen"
- Stufe 1 (sofort): Formular sendet E-Mail an mich (Formspree oder Netlify Forms)
- Stufe 2 (später): Backend-Automatisierung mit async Audit + E-Mail-Versand
- Datenschutz-Checkbox erforderlich
- Google Ads Keywords für Traffic: "BFSG Check", "Barrierefreiheit prüfen"

### TODO: Schriften lokal hosten
- Prüfen ob externe Font-URLs (Google Fonts) geladen werden
- Falls ja: WOFF2-Dateien herunterladen, nach fonts/ legen, @font-face in CSS
- Alle externen Font-URLs entfernen (DSGVO)

### TODO: DNS auf Vercel umlenken
- Bei United Domains: A-Record → 76.76.21.21 ODER CNAME → cname.vercel-dns.com
- MX-Records NICHT ändern (E-Mail muss weiter funktionieren)
- Erst umlenken, wenn Landingpage finalisiert ist

### TODO: Impressum und Datenschutzerklärung
- Pflichtangaben für deutsche Website
- Impressum: Name, Adresse, E-Mail, ggf. USt-ID
- Datenschutz: Vercel-Hosting, ggf. Analytics, Formular-Datenverarbeitung
