# Briefing: Radicle Planner

**Wat**
Een instantie van de Barentsz planner voor Radicle Ventures, gekoppeld aan hun LinkedIn company page en GitHub repo.

**LinkedIn**
Company page — ID: `106177349`
URL: linkedin.com/company/106177349

**Statusflow**
`Draft → Eindredactie → Goedgekeurd → Gepubliceerd`

Drafts worden aangeleverd door een Claude copy agent. Joost doet de eindredactie en keurt goed in de planner. Publicatie gaat direct naar de LinkedIn company page.

**GitHub-koppeling**
Na publicatie moet de definitieve posttekst automatisch worden weggeschreven naar de repo `radicle-ventures/radicle-marcom` onder:
```
archief/[jaar]-[maand]/[datum]-[slug].md
```
Dit is het leermateriaal voor de analyse agent die aan het einde van elke maand draait.

**MCP**
De planner moet beschikbaar zijn als MCP-server zodat Claude de copy agent direct posts kan aanmaken en de statusflow kan aansturen — zelfde patroon als de Barentsz planner.

**Referentie**
Volledige repo-structuur en agent-prompts: github.com/radicle-ventures/radicle-marcom
