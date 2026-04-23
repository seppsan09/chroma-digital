# chroma.digital — Projektkontext

## Wer bin ich?
Sebastian Schlunk, UX-Designer, selbständig.
Kontakt: mail@chroma.digital
LinkedIn/Xing: Sebastian Schlunk

## Was ist dieses Repo?
Landingpage für mein BFSG-Compliance-Angebot an Online-Shop-Betreiber.
Zielgruppe: deutscher Mittelstand, Fokus Möbel & Sanitär, E-Commerce allgemein.

## Hosting & Domains
- **Repo:** https://github.com/seppsan09/chroma-digital
- **Live (Vercel):** https://chroma-digital.vercel.app/
- **Geplante Domain:** chroma.digital (registriert bei United Domains)
- **E-Mail:** mail@chroma.digital (bereits eingerichtet)
- **DNS-Umzug:** steht noch aus — MX-Records für E-Mail behalten, nur A/CNAME auf Vercel ändern

## Andere Domains
- chroma-digital.de (registriert, nicht aktiv)
- chroma-digital.com (registriert, nicht aktiv)

## Tech-Stack
- Statisches HTML/CSS, kein Framework
- Deployed via Vercel (Auto-Deploy bei Push auf main)
- Stil: modern, professionell, dunkel, minimalistisch

## Angebot / Paketierung (AKTUELLE VERSION)

### Kostenloser Report (Sales-Türöffner)
- Automatisierter Kurz-Report per E-Mail
- Zeigt Risiko-Score, Ampel, Anzahl Verstöße
- Kein Preis — Ziel ist Gesprächseröffnung

### Paket 1: Compliance Report — 890€
- Vollständiger Befund: automatisierte + manuelle Tests
- Management Summary für Geschäftsführung
- Priorisierte Verstöße mit Handlungsempfehlungen
- Screenreader-Test, Alt-Text-Qualität, Tab-Navigationslogik
- Deliverable: professioneller PDF-Report
- Positionierung: "Die Diagnose" — der Kunde weiß, was kaputt ist

### Paket 2: Umsetzungs-Roadmap — ab 2.900€
- Jeder Verstoß wird ein konkretes, abarbeitbares Ticket
- Preismodell: 2.900€ inkl. 100 Tickets, jedes weitere Ticket 25€
- Pro Ticket: Screenshot IST-Zustand, CSS-Selector, konkreter Fix, Code-Snippet
- Entwickler kann Tickets ohne eigene Accessibility-Expertise abarbeiten
- Import in Jira/Linear/Asana möglich
- Positionierung: "Das Rezept" — fertige Arbeitsliste, nur noch abarbeiten
- Auf der Landingpage erklären: der Ab-Preis ergibt sich aus der Ticket-Anzahl,
  die von der Größe und Komplexität des Shops abhängt.
  Beispielrechnung: "Ein typischer Mittelstands-Shop hat 80–120 Tickets.
  Bei 100 Tickets: 2.900€. Bei 150 Tickets: 2.900€ + 50×25€ = 4.150€."

### Optional: Begleitung — 150€/Stunde
- Sprint-Support, Code-Reviews, Re-Tests
- Kein Paket, Stundensatz nach Bedarf
- Auf der Landingpage als kurzer Zusatz, nicht als gleichwertiges drittes Paket

## Inhalt der Landingpage
- Hero: BFSG-Compliance + Abmahnrisiko als Value Proposition
- Kostenloser Report als Einstieg erwähnen
- Zwei Hauptpakete: Compliance Report (890€) und Umsetzungs-Roadmap (ab 2.900€)
- Begleitung als optionaler Zusatz
- Über mich: UX-Designer, Verweis auf LinkedIn
- CTA: mail@chroma.digital
- Footer mit Impressum

## Zusammenhang mit AccessibilityScout
Das Accessibility-Repo (https://github.com/seppsan09/Accessibility) enthält das interne
Crawler-/Audit-Tool. Die Landingpage hier ist das öffentliche Gesicht.

## Offene Todos
- [ ] Landingpage mit neuer Paketierung aktualisieren
- [ ] DNS von chroma.digital auf Vercel umlenken (United Domains)
- [ ] Impressum und Datenschutzerklärung ergänzen
- [ ] Ggf. Unterseite /report mit Beispiel-Audit-Report
