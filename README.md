# harutyunyan-mariam-hw5

#### Om projektet
Projektet visar hur man hämtar, bearbetar och visualiserar data från webben.
Först hämtas Nobelprisdata för fysik via API, och motivationssträngarna extraheras och analyseras med ett ordmoln för att identifiera vanliga teman.
Sedan skrapas de tre första sidorna på Books to Scrape för att samla information om 60 böcker, inklusive UPC, titel, pris och betyg.
Syftet är att demonstrera praktiska färdigheter i API-anrop, JSON-hantering, webbskrapning, textanalys och visualisering med fokus på reproducerbarhet och tydlig kodstruktur.

#### Miljökrav
- **Python 3.10+**
- **Jupyter Notebook**,
- **Paket: se filen 'requirements.txt'**

#### Reproducerbarhet
1. Installera Anaconda (eller Miniconda) som inkluderar Jupyter Notebook.
2. Installera nödvändiga Python-paket:
    ```bash
    pip install -r requirements.txt
    ```
3. Öppna projektet i Jupyter Notebook.
4. Kör notebooken **uppifrån och ner**.

#### Viktigt 
- Notera att notebooken är uppbyggd så att paket importeras i den första cellen samt variabler och funktioner definieras i de tidiga cellerna. För att alla celler ska fungera korrekt måste därför notebooken köras i ordning, uppifrån och ner. 
- API-anrop: Nobel-API-anrop kan ta någon minut
- Koden skapar en mapp 'data' och sparar all data som hämtas i denna mapp.
- Varje gång koden körs hämtas all data på nytt i till mappen 'data'
- Data som denna Notebook använder under tillfället för resultat som syns på Github följer med sparad i en extra mapp döpt 'data2025-12-07'