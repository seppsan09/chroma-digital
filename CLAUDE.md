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

## Vorher auf chroma.digital
Eine Seite über 3D-Visualisierung, gehostet per SFTP (Cyberduck) auf United-Domains-Webspace.
Wird durch die neue Landingpage ersetzt, sobald DNS umgelenkt wird.

## Andere Domains
- chroma-digital.de (registriert, nicht aktiv)
- chroma-digital.com (registriert, nicht aktiv)

## Tech-Stack
- Statisches HTML/CSS, kein Framework
- Deployed via Vercel (Auto-Deploy bei Push auf main)
- Stil: modern, professionell, dunkel, minimalistisch

## Inhalt der Seite
- Hero: BFSG-Compliance + Abmahnrisiko als Value Proposition
- Drei Pakete: Quick Check (490€), WCAG-Audit (2.500€), Umsetzung (auf Anfrage)
- Über mich: UX-Designer, Verweis auf LinkedIn
- CTA: mail@chroma.digital
- Footer mit Impressum

## Zusammenhang mit AccessibilityScout
Das Accessibility-Repo (https://github.com/seppsan09/Accessibility) enthält das interne
Crawler-/Audit-Tool, das die Leads generiert. Die Landingpage hier ist das öffentliche
Gesicht für die Kundenansprache. Der automatisierte PDF-Report (wird noch gebaut)
wird aus dem Accessibility-Tool generiert und per mail@chroma.digital verschickt.

## Offene Todos
- [ ] DNS von chroma.digital auf Vercel umlenken (United Domains)
  - A-Record → 76.76.21.21 ODER CNAME → cname.vercel-dns.com
  - MX-Records NICHT ändern (E-Mail muss weiter funktionieren)
- [ ] Impressum und Datenschutzerklärung ergänzen
- [ ] Ggf. Unterseite /report mit Beispiel-Audit-Report
- [ ] Cookie-Banner (falls Analytics eingebaut wird)
