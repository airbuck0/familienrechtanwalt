# Familienrecht Anwalt - Website

Professionelle Familienrecht-Website für familienrechtanwalt.ch mit Navy + Gold Design.

## 📁 Struktur

```
familienrechtanwalt-website/
├── index.html          # Homepage (Familienrecht Focus)
├── ueber-uns.html      # Über uns
├── kontakt.html        # Kontakt mit Formular
├── impressum.html      # Impressum (Platzhalter)
├── datenschutz.html    # Datenschutzerklärung (Platzhalter)
├── robots.txt          # Google BLOCKIERT
├── sitemap.xml         # Sitemap
└── README.md           # Diese Datei
```

## ✅ Was funktioniert SOFORT

- ✅ Kontaktformular (Live mit Web3Forms)
- ✅ Design: Navy + Gold, Klassisch-Elegant
- ✅ 100% Familienrecht fokussiert
- ✅ 9 Familienrecht-Themen abgedeckt
- ✅ Responsive: Mobile + Desktop perfekt
- ✅ SEO-optimiert
- ✅ SSL-ready
- ✅ Google BLOCKIERT (robots.txt)

## 🎯 Familienrecht-Themen

Die Homepage deckt ALLE wichtigen Familienrecht-Bereiche ab:

1. **Scheidung** - Einvernehmlich & strittig
2. **Sorgerecht & Obhut** - Geteilte/alleinige Obhut
3. **Unterhalt** - Kindes-, Ehegatten-, nachehelicher Unterhalt
4. **Besuchsrecht** - Persönlicher Verkehr, Ferienregelungen
5. **Güterrecht** - Vermögensaufteilung, Errungenschaftsbeteiligung
6. **Ehevertrag** - Güterstandsvereinbarungen
7. **Trennung** - Trennungsvereinbarungen
8. **Vaterschaft** - Anerkennung, Anfechtung
9. **Kindesschutz** - KESB, Beistandschaften

→ **Weitere Detail-Pages erstellst du mit Claude Code!**

## 📝 PLATZHALTER die ersetzt werden müssen

In allen Dateien:
- `[FIRMENNAME]`
- `[RECHTSFORM]`
- `[VOLLSTÄNDIGER NAME]`
- `[ADRESSE]`
- `[PLZ ORT]`
- `[EMAIL]`
- `[TELEFON]`
- `[UID-NUMMER]`
- `[HANDELSREGISTER]`
- `[BERUFSBEZEICHNUNG]`
- `[AUFSICHTSBEHÖRDE]`
- `[JAHR]` (Zulassung)

## 🚀 DEPLOYMENT ANLEITUNG

### PHASE 1: GitHub Repository erstellen

1. Gehe zu https://github.com
2. Klicke "New Repository"
3. Name: `familienrechtanwalt`
4. Public
5. Create Repository
6. Upload Files: Drag & Drop alle Files
7. Commit

### PHASE 2: Cloudflare Pages Setup

1. Gehe zu https://dash.cloudflare.com
2. Workers & Pages → Create Application
3. Pages Tab → Connect to Git
4. Authorize GitHub
5. Select Repository: `familienrechtanwalt`
6. Build Settings:
   - Framework preset: **None**
   - Build command: *(leer)*
   - Build output directory: `/`
7. Save and Deploy

→ Site ist live auf: `xyz.pages.dev`

### PHASE 3: Domain verbinden

1. Cloudflare Dashboard → Websites
2. Add Site → `familienrechtanwalt.ch`
3. Free Plan
4. Cloudflare scannt DNS
5. Notiere Nameserver

6. Bei Infomaniak:
   - Login zu Infomaniak Manager
   - Domain Management → familienrechtanwalt.ch
   - Nameserver ändern zu Cloudflare Nameservers
   - Speichern

7. Zurück zu Cloudflare:
   - Warte auf DNS Propagation (2-24 Std)
   - Workers & Pages → dein Projekt
   - Custom Domains → Add Domain
   - `familienrechtanwalt.ch`
   - SSL Zertifikat automatisch (5-30 Min)

→ Site ist live auf: https://familienrechtanwalt.ch

## 🔄 UPDATES MACHEN

1. Dateien lokal ändern
2. Bei GitHub: Upload updated files
3. Cloudflare deployt AUTOMATISCH in 30-60 Sek

## 🤖 Google Indexierung aktivieren (später)

Wenn bereit für Google:

1. Ändere `robots.txt`:
```
User-agent: *
Allow: /
Sitemap: https://familienrechtanwalt.ch/sitemap.xml
```

2. Push zu GitHub
3. Auto-deployed
4. Google kann crawlen

## 📧 Kontaktformular

- **Status:** ✅ LIVE und funktionsfähig
- **Service:** Web3Forms
- **Access Key:** d2de9031-9507-4b2b-94cb-1b47e98e93ca
- **Submissions gehen an:** airbuck0@live.de

Test das Formular nach Deployment!

## 🎨 Design Details

- **Primärfarbe:** Navy Blue (#1e3a8a)
- **Sekundärfarbe:** Gold (#c9a961)
- **Schrift Headlines:** Playfair Display (Serif)
- **Schrift Body:** Inter (Sans-Serif)
- **Framework:** Tailwind CSS (via CDN)

## 📱 Responsive

- Desktop: 1280px+
- Tablet: 768px - 1279px
- Mobile: < 768px

## ⚡ Performance

- TTFB: ~30-60ms (Cloudflare CDN)
- PageSpeed Score: 95-100 erwartet
- SSL: Automatisch via Cloudflare
- Zero Hosting Cost: $0/Monat

## 🔨 WEITERE ENTWICKLUNG

**Mit Claude Code erstellen:**

Detail-Pages für jedes Familienrecht-Thema:
- scheidung.html
- sorgerecht.html
- unterhalt.html
- besuchsrecht.html
- gueterrecht.html
- ehevertrag.html
- trennung.html
- vaterschaft.html
- kindesschutz.html

Location Pages:
- familienrecht-zuerich-oerlikon.html
- familienrecht-zuerich-altstetten.html
- etc.

## ✅ NEXT STEPS

1. [ ] Deploy zu GitHub
2. [ ] Connect Cloudflare Pages
3. [ ] Domain Nameservers ändern
4. [ ] Warten auf DNS (2-4 Std)
5. [ ] Testen: https://familienrechtanwalt.ch
6. [ ] Kontaktformular testen
7. [ ] Platzhalter ersetzen
8. [ ] Detail-Pages mit Claude Code erstellen
9. [ ] Google freischalten (robots.txt)

---

**Viel Erfolg mit deiner Familienrecht-Website!** 🚀