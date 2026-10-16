# Briefing: nieuwe website Elektriciteitswerken Boon (elecboon.be)

Opdrachtgever: Wizarts (Stijn De Pauw), voor klant Boon bv, Lokeren.
Stack: statische site in HTML, CSS en vanilla JS. Geen framework, geen build-stap nodig.

---

## 0. Eerst doen: skills kiezen (voor je iets bouwt)

1. Inventariseer welke skills lokaal beschikbaar zijn (persoonlijke skills, projectskills in `.claude/skills/`, en skills uit geïnstalleerde plugins).
2. Lees van elke relevante skill de `SKILL.md`.
3. Stel voor welke skill(s) je wil gebruiken voor deze opdracht en waarom (bv. een frontend/design-skill voor de visuele richting, een audit-skill om het resultaat te checken).
4. **Wacht op mijn akkoord** voor je begint te bouwen.

Daarna: lees deze briefing volledig, bekijk de aangeleverde mappen en geef een kort plan (sitestructuur + visuele richting in een paar zinnen) voor je code schrijft.

---

## 1. Aangeleverde bestanden

| Map / bestand | Inhoud | Wat ermee doen |
|---|---|---|
| `index.html` (voorbeeld) | Eerste ontwerpvoorstel | Referentie voor sfeer en inhoud. **Niet** als basis kopiëren, zie punt 3 |
| `img/` | Projectfoto's en stockbeelden | Gebruiken waar ze passen, optimaliseren (zie punt 9) |
| `partners/` | Logo's van klanten en merken | Enkel de logo's uit punt 6 gebruiken |

Zoek het **bestaande Boon-logo** in de aangeleverde mappen. Vind je het niet: zet een duidelijke placeholder en meld het.

---

## 2. Over de klant

- Elektriciteitswerken Boon, familiebedrijf, opgericht in 1983 door Robert Boon. Robby Boon stapte in 1995 in (2e generatie). Sinds 2008 Boon bv.
- Diensten: algemene elektriciteitswerken, domotica en centrale sturing, data en netwerk, verlichting. Voor woningen, kantoren en industrie.
- Werkgebied: Waasland en ruimer.

### Doelgroep: OPGELET, vooral B2B

De site moet in de eerste plaats spreken tot **professionele opdrachtgevers**:

- Bouwbedrijven, aannemers en sleutel-op-de-deurbouwers. Ook de **woningen** die Boon doet, zijn vaak projecten voor bouwbedrijven (B2B), niet enkel voor particulieren.
- Bedrijven, kantoren en industrie.
- Particulieren blijven welkom, maar zijn niet de hoofddoelgroep.

Dit moet je merken in toon, volgorde van de secties en CTA's (bv. "Samenwerken op uw project", "Offerte voor uw werf").

---

## 3. Het voorbeeld: enkel inspiratie

**Je mag een volledig andere site maken dan het voorbeeld.** Gebruik het enkel als inspiratie voor sfeer en inhoud. Het voorbeeld is leuk, maar voelt als **AI-slop** en de **UX is minder**.

Uitgangspunten voor de nieuwe site:
- **Professioneel**: rustig, zelfzeker, vakmanschap uitstralen. Geen effecten om de effecten.
- **Gestructureerd**: duidelijke hiërarchie, logische volgorde, consistente componenten en spacing.
- **Gebruikersgericht**: vertrek vanuit wat de bezoeker (vooral een bouwbedrijf of bedrijf) wil weten en doen. Kan Boon dit? Hebben ze dit al gedaan? Hoe neem ik contact op? Elke sectie moet daar een antwoord op geven.

Werk eerst de gebruikersbehoeften en de sitestructuur uit en pas daarna de visuele laag.

### Mag als inspiratie dienen
- Grote, zelfzekere typografie en een sterke hero met projectfoto.
- Duidelijke diensten-overzicht.
- Projecten met filter.
- Tijdlijn van het familiebedrijf (1983, 1995, 2008).
- Contactblok met alle gegevens en een offerteformulier.

### Weg of herdenken (AI-slop)
- De lichtschakelaar-gimmick in de hero.
- "F1, F2 ..." zekeringkast-labels boven elke sectie.
- Draaiende badge, schuine marquee-band, getekende onderstreping, tellende cijfers.
- Domotica-"scènes" die klikbaar zijn maar niets doen.
- De probleem/oplossing-sectie met rode kruisjes: te sjabloonmatig. Als je bezwaren wil behandelen, doe het kort en concreet vanuit B2B-standpunt.
- Vage cijfers zoals "30+ referentieprojecten in beeld".
- Generieke slogans ("Stroom die klopt.").

### UX-problemen om op te lossen
- Op mobiel verdwijnt de navigatie zonder hamburgermenu: zorg voor een werkend mobiel menu.
- Projectfilter dimt items in plaats van ze te tonen/verbergen: echt filteren.
- Dezelfde foto wordt meermaals gebruikt (hero en galerij).
- Formulier doet niets: zie punt 9.
- Telefoonnummer moet op mobiel altijd binnen één tik bereikbaar zijn (sticky bel-knop of in de header).
- Eén duidelijke primaire CTA, niet overal een andere.

---

## 4. Huisstijl

- **Kleuren: zwart, grijs en rood.** De klant houdt van **zwart**: zwart mag dominant zijn (donkere secties, header, hero). Grijstinten voor vlakken en tekst, rood als accent (CTA's, details). Geen lime en geen blauw zoals in het voorbeeld.
- Zorg voor voldoende contrast (WCAG AA), ook rood op zwart.
- **Logo behouden** zoals het is. **Groot plaatsen bovenaan** (hero / eerste scherm), daarna kleiner in de sticky header.
- Typografie: kies zelf een stevig, technisch maar warm duo. Niet automatisch de fonts uit het voorbeeld overnemen. Licht en donker thema is niet nodig: één (donkere) look is prima, tenzij je een goed argument hebt.

---

## 5. Kernboodschap (USP)

Werk de USP uit in de richting van:

> **Ervaring in technische en complexe installaties en automatisatie.**

Ondersteunende argumenten (verder uitwerken, kort houden):
- Meer dan 40 jaar ervaring, twee generaties.
- Complexe projecten snel en correct aangepakt (zie ISS-case).
- Vaste partner van bouwbedrijven: planning afgestemd op de werf, één aanspreekpunt.
- Al sinds de jaren negentig gespecialiseerd in centrale sturing en domotica.
- Werken volgens het AREI, met schema's en keuring in orde.

Geef 2 à 3 varianten voor de hero-titel en ondertitel, zodat we kunnen kiezen.

---

## 6. Klanten en partners

Op de huidige site staan veel logo's; de meeste mogen weg. **Enkel deze tonen:**

**Klanten**
- ISS (topklant)
- Volvo Truck Center (VTC)
- Bluebridge
- ABS Bouwteam

**Merken / leveranciers**
- ABB (automaten)
- Schneider Electric
- Delta Light

**Weg:** Hager, Modular Lighting Instruments, Wever & Ducré, Elbeko en alle andere.

Splits klanten en merken visueel op (twee rijen of twee blokken). Ontbreekt een logo in `partners/`: placeholder met de naam en melden in je eindrapport.

---

## 7. Projecten / realisaties

**Categorieën (filter):** Woningen · Domotica · Industrie & kantoor

**Te behouden projecten:**
- **ISS** (Industrie & kantoor), uit te werken als **uitgebreide case** (zie hieronder)
- **Woning Hertsberge** (Woningen)
- **Woning Turnhout** (Woningen, Domotica)

Alle andere projecten uit het voorbeeld mogen weg. **Nieuwe projecten volgen nog**, dus:
- Bouw de projecten **data-gedreven**: één JS- of JSON-bestand (`projects.js` of `projects.json`) met per project: titel, locatie, categorie(ën), korte tekst, foto's, optioneel link naar case. Een nieuw project toevoegen = één object toevoegen.
- Zorg dat het overzicht er ook goed uitziet met maar 3 projecten.

### Case ISS
- Insteek: **complex project, snel aangepakt**.
- Gekend: kantoorproject van ca. 5000 m².
- Structuur: opdrachtgever, uitdaging, aanpak, resultaat, foto's.
- Concrete details (timing, scope, systemen) ontbreken nog: zet duidelijke placeholders (`[TE BEVESTIGEN: ...]`) die we later invullen.
- Mag een eigen pagina zijn (`projecten/iss.html`) of een uitklapbare case op de projectpagina. Kies wat het best werkt en motiveer.

---

## 8. Reviews

- Toon een sectie met reviews / getuigenissen van tevreden klanten: **ISS** en **Volvo Truck Center**.
- De echte teksten volgen nog. Schrijf voorlopig **voorbeeldteksten**, maar markeer ze duidelijk als placeholder:
  - in de data (`"placeholder": true`) en met een HTML-commentaar `<!-- PLACEHOLDER: vervangen door echte, goedgekeurde review -->`;
  - verzin geen namen van personen, gebruik enkel bedrijfsnaam + functie (bv. "Facility manager, ISS").
- Deze reviews mogen **niet live** gaan voor de klant ze heeft aangeleverd of goedgekeurd. Neem dit op in de checklist van punt 11.

---

## 9. Inhoud en praktische gegevens

### Contact
- Telefoon: 052 44 73 66
- Gsm: 0472 41 40 36
- E-mail: info@elecboon.be
- Kantoor: Heiendestraat 92, 9160 Lokeren
- **Magazijn (nieuw adres): Bouwstraat 14 C6, 9160 Lokeren** (vervangt Voermanstraat, Zele)

### Voorgestelde structuur (one-pager of klein aantal pagina's, motiveer je keuze)
1. Header: logo, navigatie, telefoon, CTA
2. Hero: groot logo, USP, CTA
3. Diensten: woningen, domotica, data & netwerk, industrie & kantoor
4. Waarom Boon (USP-argumenten, B2B-gericht)
5. Projecten met filter + ISS-case
6. Reviews
7. Klanten en merken
8. Over ons: tijdlijn familiebedrijf
9. Contact + offerteformulier
10. Footer: adressen, btw-nummer (`[TE BEVESTIGEN]`), privacy

### Copyregels
- Nederlands (Vlaams), aanspreking met **"u"** (B2B).
- Kort, concreet, zonder opvulling. Resultaatgericht: wat heeft de klant eraan.
- **Geen em dashes (—)**.
- **Geen "geen X, wel Y"-constructies.**
- **Geen komma voor "en".**
- Titels in **sentence case**.
- Geen verzonnen cijfers of feiten. Onbekend = `[TE BEVESTIGEN: ...]`.

---

## 10. Technische eisen

- HTML, CSS en vanilla JS. Semantische HTML, CSS custom properties voor kleuren en spacing.
- Mobile first, getest op 360px, 768px, 1024px en 1440px. Geen horizontale scroll.
- Toegankelijkheid: WCAG AA-contrast, focus-states, alt-teksten, toetsenbordbediening, `prefers-reduced-motion` respecteren.
- Animaties: spaarzaam en functioneel (subtiele reveal of hover is oké).
- Performance: afbeeldingen omzetten naar WebP/AVIF in meerdere formaten (`srcset`), lazy loading onder de vouw, fonts met `font-display: swap`. Streef naar Lighthouse 90+ op alle onderdelen.
- SEO: unieke title en meta description, Open Graph, `LocalBusiness`/`Electrician` schema.org met beide adressen en telefoon, `sitemap.xml`, `robots.txt`.
- Formulier: markup en validatie volledig uitwerken. Verzending voorlopig via een eenvoudig te vervangen endpoint (bv. Formspree of een PHP-mailscript, configureerbaar bovenaan in de JS). Melding bij succes en fout. Klikbare `tel:` en `mailto:`-links.
- Projecten en reviews uit databestanden (zie punten 7 en 8).
- Mappenstructuur: `index.html`, `css/`, `js/`, `img/`, `partners/`, `data/`, eventueel `projecten/`.

---

## 11. Oplevering en checklist

Lever op met een korte `README.md`: structuur, hoe een project of review toevoegen, waar het formulier-endpoint staat.

Check voor je zegt dat het af is:
- [ ] Skills gekozen en goedgekeurd (punt 0)
- [ ] Logo groot in hero, kleiner in header
- [ ] Kleuren zwart, grijs, rood; contrast AA
- [ ] B2B-toon en CTA's
- [ ] Nieuw magazijnadres: Bouwstraat 14 C6, 9160 Lokeren
- [ ] Enkel de toegelaten klanten/merken
- [ ] Projectcategorieën: Woningen / Domotica / Industrie & kantoor; filter werkt echt
- [ ] ISS-case uitgewerkt met placeholders
- [ ] Reviews gemarkeerd als placeholder, niet live zonder goedkeuring klant
- [ ] Werkend mobiel menu, bel-knop op mobiel
- [ ] Geen em dashes, geen "geen X, wel Y", geen komma voor "en"
- [ ] Lighthouse 90+ mobiel
- [ ] Lijst met alle `[TE BEVESTIGEN]`-punten en ontbrekende logo's/foto's in je eindrapport

---

## 12. Open punten (nog te bevestigen bij de klant)

- Exacte inhoud en cijfers van de ISS-case
- Echte reviews van ISS en Volvo Truck Center
- Logo's van Bluebridge, Volvo Truck Center, ABS Bouwteam, ABB (indien niet in `partners/`)
- Btw-nummer en eventuele erkenningen/certificaten
- Extra projecten
