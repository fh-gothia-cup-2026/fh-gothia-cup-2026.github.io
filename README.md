# FH · Gothia Cup 2026 — Ferðahandbók

Static, single-page handbook for FH 4. flokkur karla at Gothia Cup 2026
(Gautaborg, 12.–19. júlí 2026). Built in Icelandic, modelled on the
[multabene.is/gothia](https://www.multabene.is/gothia) handbook.

## Skrár

```
index.html         # Öll síðan (HTML + CSS + JS í einni skrá)
assets/fh-logo.svg # FH merki (af Wikimedia Commons)
README.md
```

## Að skoða

Tvísmelltu á `index.html` til að opna í vafra. Engin uppsetning nauðsynleg.

## Hýsing á GitHub Pages

Síðan er hýst ókeypis á **GitHub Pages** beint úr þessu git-safni (repo). Slóðin er:

```
https://<notandi>.github.io/<repo>/
```

Þegar einhver breytir `index.html` á github.com (sjá næsta kafla) uppfærist vefurinn
sjálfkrafa eftir u.þ.b. 1 mínútu.

### Kveikja á Pages (gert einu sinni)

Repo á github.com → **Settings → Pages → Build and deployment**:
- **Source:** „Deploy from a branch“
- **Branch:** `main`, mappa `/ (root)` → **Save**

## Hvernig á að breyta síðunni (fyrir alla — engin forritun)

1. Farðu í repo-ið á github.com og **skráðu þig inn** (ókeypis GitHub aðgangur).
   Eigandi bætir þér við undir **Settings → Collaborators** svo þú getir breytt.
2. Smelltu á `index.html` og svo á ✏️ **„Edit this file“** blýantinn efst til hægri.
   (Eða ýttu á `.` í repo-inu til að opna fullan ritil, `github.dev`.)
3. Notaðu **Ctrl+F** til að finna textann sem á að breyta. **Breyttu aðeins textanum á
   milli `>` og `<`** (t.d. innihaldi `<p>...</p>`). Ekki snerta merkin sjálf, `class="..."`,
   né `href`/`src` slóðir.
4. Skrunaðu niður → **„Commit changes“** (vista beint á `main`).
5. Bíddu ~1 mínútu og endurhladdu vefinn. Allar breytingar eru öruggar — undir **History**
   í repo-inu má alltaf afturkalla („Revert“) breytingu.

> 💡 Allar breytingar eru útgáfustýrðar (version history), svo ekkert glatast og auðvelt
> er að fara til baka ef eitthvað brotnar.

Mundu að `assets/`-mappan (FH-merkið) þarf alltaf að fylgja með.

## Eiginleikar

- Föst valmynd efst sem stökkva á kafla; fellur í ☰ á síma.
- „Prenta / Vista sem PDF“ hnappur með sérstöku prentútliti.
- Pökkunarlistinn man hökin (geymt í vafranum, `localStorage`).
- Hannað fyrir síma fyrst (foreldrar skoða mest í síma).
- **Staðsetningarkortið (kafli 12)** er Google „My Maps“ kort sem er fellt inn (embed).
  Til að breyta pinnum: opnaðu kortið í Google My Maps og breyttu þar — síðan uppfærist
  sjálfkrafa (ekki þarf að breyta `index.html`). `assets/gothia-stadir.kml` er afrit af
  pinnunum (réttar staðsetningar) — hægt að flytja það inn í nýtt Google My Maps á öðrum
  aðgangi til að endurnýta kortið. Uppfærðu `mid=` í embed-slóðinni í `index.html` ef nýtt kort er búið til.

## TODO — fylla inn í `index.html` þegar upplýsingar liggja fyrir

Leitaðu að `VANTAR` / `class="todo"` í skránni:

1. **Hegðunarsáttmáli** (kafli 9) — setja útivistartíma / hvenær skólinn lokar.
2. **Úrslitakeppni** (kafli 3) — leikir fimmtud.–laugard. birtast þegar staða úr riðlum liggur fyrir.
3. **Þjálfarar** (kafli 1) — fullt nafn á „Arnar“ ef óskað er (símanúmer er skráð).

Riðlarnir í kafla 4 (Liðaskipan) eru sóttir af results.gothiacup.se. Hver riðill hefur
„Lifandi staða“ tengil á opinberu mótssíðuna þar sem röð og úrslit uppfærast meðan á mótinu stendur.

Allar dagsetningar, tímar og símanúmer eru tekin beint úr Google-skjalinu —
gott að lesa yfir áður en síðan er birt.

## Heimildir fyrir merki

FH-merkið er sótt af Wikimedia Commons:
<https://commons.wikimedia.org/wiki/File:Logo_FH_Hafnarfj%C3%B6rdur.svg>
