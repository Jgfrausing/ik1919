# [IK1919](www.ik1919.dk)
Siden er udviklet med [Hugo](https://gohugo.io/), som er template baseret styling til statiske hjemmesider.
Templaten brugt er [Academic Kickstart](https://sourcethemes.com/academic/) med modificationer.

Der er mange fordele ved Hugo:
- En færdigtdesignet template gør, at vi ikke skal stå for den kunstneriske del af at lave en hjemmeside
- Styling kan genbruges ved f.eks. trænere og bestyrelses medlemmer
- Templaten er kun et forslag, hvilket betyder, at vi kan let kan lave ændringer deri (f.eks. baggrunds billedet)
- Både MarkDown og HTML kan anvendes til styling

## Installation af Hugo
### Windows
1. [Download version 56.3 from this link](https://github.com/gohugoio/hugo/releases/download/v0.56.3/hugo_extended_0.56.3_Windows-64bit.zip)
2. Create the folder `C:\Hugo\bin` and extract the downloaded content into it
3. Tilføj `C:\Hugo\bin` til `Systemvariabler`
    - Højreklik `Denne Computer` og klik `Egenskaber`
    - Klik `Avanceret systemindstilling` og derefter `Miljøvariabler` 
    - Under `Systemvariabler` dobbeltklik på variablen `Path` og tryk `Ny`
    - Skriv `C:\Hugo\bin` i feltet og tryk `OK`

### Linux og Mac
1. Åben terminal og kør `brew install hugo`
    - Brew kan installeres til Linux ([se link](https://docs.brew.sh/Homebrew-on-Linux))

## Download projektet
1. Åben en terminal og kør: `git clone https://github.com/Jgfrausing/ik1919.git`

## Se ændringer lokalt:
1. Åben mappen ik1919, højreklik deri og tryk `Åben i terminal`
2. Indtast `hugo server` og tryk enter
    - Nederst i terminalen vil der stå `Web Server is available at //localhost:1313/ (bind address 127.0.0.1)`
3. Åben en browser og skriv `//localhost:1313/` (den adresse der står i terminalen)

## Opload nye ændringer til ik1919.dk
1. Åben mappen ik1919, højreklik deri og tryk `Åben i terminal`
2. Indtast `hugo` og tryk enter
    - Dette opretter/overskriver mappen `public`
3. Forbind til serveren via FileZilla eller ligende og erstat indholdet der med indholdet i `public`

**Husk at pushe ændringerne til github**