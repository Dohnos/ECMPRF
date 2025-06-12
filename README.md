# ECMPRF

Tento projekt je ukázkový web pro prezentaci různých oblastí pracovního a společenského života ve společnosti Profesia. Web je určen jako jednoduchý portál pro studenty, absolventy nebo zájemce o brigády, pracovní nabídky, kulturní akce a komunitní dění.

## O projektu

Web slouží jako statická ukázka portálu, kde uživatelé mohou:
- Prohlížet aktuální pracovní nabídky v různých oborech (IT, marketing, recepce, podpora atd.)
- Najít brigády vhodné pro studenty
- Číst blogové články s tipy a zkušenostmi
- Získat přehled o kulturních akcích

Každá sekce má vlastní HTML stránku, nabídky práce jsou navíc strukturovány v samostatných souborech a data jsou uložena v JSON formátu.

## Použité technologie

- **HTML5** – pro strukturu webových stránek
- **CSS3** – pro stylování (složka `css/` a zdrojové SCSS ve složce `scss/`)
- **SCSS** – preprocesor pro CSS (zdrojový soubor `scss/style.scss`, výsledný CSS v `css/style.css`)
- **JSON** – pro data nabídek práce (`nabidky/nabidky.json`)

## Struktura projektu

```
.  
├── blog.html              # Stránka blogu
├── brigady.html           # Stránka s brigádami
├── forum.html             # Stránka fóra
├── index.html             # Hlavní stránka
├── kultura.html           # Stránka o kultuře
├── css/
│   └── style.css          # Sestylovaný CSS soubor
├── scss/
│   ├── style.scss         # Zdrojový SCSS soubor
│   └── style.css.map      # Mapování pro ladění SCSS
├── nabidky/
│   ├── backend.html       # Nabídka práce: Backend
│   ├── frontend.html      # Nabídka práce: Frontend
│   ├── marketing.html     # Nabídka práce: Marketing
│   ├── recepcna.html      # Nabídka práce: Recepční
│   ├── support.html       # Nabídka práce: Support
│   └── nabidky.json       # Data nabídek práce
```

## Poznámky
- Pro správné zobrazení je potřeba mít zachovanou strukturu složek.
- Web podporuje tmavý režim (dark mode) pomocí CSS.
- Pro inspiraci při hledání práce byl využit nástroj Perplexit, kde uživatel v action button zadá informace co ho baví, silné stránky atd a otevře se Perplexity, které mu dodá informace a inspiraci.
