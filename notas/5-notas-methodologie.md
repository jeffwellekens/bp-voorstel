# Fase 5. Methodologie

- **Werktitel onderzoeksvoorstel:** VUL HIER JE TITEL IN
- **Naam Student 1:** VOORNAAM FAMILIENAAM
- **Naam Student 1:** VOORNAAM FAMILIENAAM (of verwijder deze lijn als je alleen werkt)
- **URL Github repo:** <https://github.com/HoGentTIN/rm-2223-paper-rmAANVULLEN>

## Plan van aanpak

- **Fase 1: NAAM**
  - **Doelstelling:** AANVULLEN
  - **Aanpak:**
    - AANVULLEN
  - **Resultaat, deliverable(s):** AANVULLEN
- **Fase 2: NAAM**
  - ...

## Verloop

Gebruik (een) Mermaid-diagram(men) om de stappen of het tijdverloop de visualiseren (flowchart en/of Gantt-diagram; zie instructies).

1.  Literatuurstudie om meer inzicht te krijgen in wat de verschillen zijn tussen de twee blazor hostingmodellen. En ook wat de nieuwe functies zijn in .NET 8 die ons kunnen helpen
    om het beste van beide hostingmodellen te benutten.
2.  Experiment uitvoeren waarbij in beide hostingmodellen op een zelfgemaakt applicatie testen worden uitgevoerd in verband met laadtijd, netwerkprestaties, crawling van de pagina voor seo.
3.  Resultaten interpreteren die voortkomen uit het experiment, kijken welk hostingmodel de snelste laadtijd en netwerkprestaties heeft. Ook welke hostingmodel het best geschikt is voor seo. Ook belangrijk is dat we bekijken hoe de nieuwste functies in .NET 8 ons kunnen helpen om beide hostingmodellen zo optimaal mogelijk te gebruiken.

```mermaid
flowchart TD
    A[Literatuuronderzoek] --> B[Applicatie bouwen]
    B --> C[Experiment uitvoeren]
    C --> D[Gegevensanalyse]
    D --> E[Interpretatie en conclusie]
```

```mermaid
gantt
    title tijdsverloop
    dateFormat  YYYY-MM-DD
    Literatuuronderzoek :a1, 2024-01-01, 14d
    Applicatie bouwen :b1, after a1, 14d
    Experiment uitvoeren :c1, after b1, 14d
    Gegevensanalyse :d1, after c1, 7d
    Interpretatie en conclusie :e1, after d1, 14d
```

<!-- Aanpassen van methodologie -->
