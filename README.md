# WohnungsApp – „Kann ich mir das leisten?"

Ein Rechner für den **Wohnungskauf in Deutschland**: Du gibst Eigenkapital und
Dein monatliches Budget ein und siehst sofort, ob sich eine Wohnung ausgeht –
inklusive **Kaufnebenkosten, Förderung und Steuer**, wahlweise für
**Eigennutzung** oder **Vermietung**.

Alles läuft **offline im Browser** – es werden keine Eingaben übertragen oder
gespeichert.

## Was die App rechnet

- **Dein Geld:** Eigenkapital und was pro Monat fürs Wohnen übrig ist.
- **Objekt & Kaufnebenkosten:** Kaufpreis, Wohnfläche (→ Preis pro m²),
  **Grunderwerbsteuer automatisch je Bundesland** (Stand 2025), Notar &
  Grundbuch, Maklerprovision.
- **Finanzierung:** Sollzins und anfängliche Tilgung → monatliche Rate, plus
  Beleihungs-Check (LTV) und ein Hinweis, wenn das Eigenkapital nicht einmal die
  Nebenkosten deckt.
- **Förderung:** ein zinsgünstiges **KfW-Förderdarlehen** (ersetzt einen Teil des
  Bankdarlehens zum Förderzins) und/oder ein **einmaliger Zuschuss**.
- **Nutzung umschaltbar:**
  - **Eigennutzung** – monatliche Belastung gegen Dein Budget, Ampel
    (leistbar / knapp / zu teuer) und eine Orientierung, bis zu welchem
    Kaufpreis es tragbar wäre.
  - **Vermietung** – monatlicher Cashflow inkl. **Steuerwirkung** (AfA, absetzbare
    Zinsen, nicht umlagefähige Kosten, Grenzsteuersatz), dazu Brutto- und
    Nettomietrendite. Die Tilgung wird als Vermögensaufbau separat ausgewiesen.

## Nutzen

Einfach `index.html` im Browser öffnen. Kein Server, keine Installation.

### Als Website (GitHub Pages)

`Settings → Pages → Source: Deploy from a branch → main / (root)`. Danach ist die
App unter `https://alfredjdh.github.io/WohnungsApp/` erreichbar.

## Annahmen (bewusst vereinfacht)

- Gerechnet wird das **erste Jahr** als Momentaufnahme (die Rate bleibt gleich,
  der Zinsanteil sinkt über die Laufzeit).
- AfA-Bemessung = Gebäudeanteil der gesamten Anschaffungskosten × AfA-Satz.
- Grunderwerbsteuersätze Stand 2025, im Feld manuell überschreibbar.

Das ist eine **grobe Orientierung, keine Steuer- oder Finanzberatung**. Konkrete
Konditionen mit Bank, Steuerberatung und Förderstelle (z. B. KfW) prüfen.
