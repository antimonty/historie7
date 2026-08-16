# Kulturfag 7. Klasse - Grundbog og Laesehjaelp

Dette repository indeholder en skraeddersyet laeser-portal (Reader Hub) til 7. klasses undervisning i kulturfag (historie og samfundsfag).

Formaalet med sitet er at levere en responsiv, reklamefri og laesevenlig visning af kildemateriale og faglige tekster til brug paa computere, tablets og i Microsoft Teams.

## Funktioner
* Automatisk laesetilstand: Renderer indhold dynamisk via Mozilla Readability i et rent og responsivt layout med fuld skaermbredde.
* Bevarer kildebilleder: Billeder og illustrationer traekkes med over og skaleres automatisk til artikelflowet.
* Integreret i Teams: Fungerer som fast laesefane i klassens Teams-kanal.

## Teknisk opbygning
* Frontend: Statisk HTML5, CSS og ren JavaScript.
* Parsing og Sikkerhed: @mozilla/readability og DOMPurify.
* Proxy-kald: Henter data on-the-fly via CORS-proxy (corsproxy.io / allorigins.win).
* Hosting: GitHub Pages.

## Ophavsret
Sitet lagrer intet indhold permanent paa serveren. Alle tekster og billeder parses og visualiseres on-the-fly i elevens browser fra frit tilgaengeligt onlinemateriale.
