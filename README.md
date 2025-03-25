# HelloFresh Scraper & Shopping List Generator

Een webapplicatie voor het automatisch genereren van boodschappenlijstjes op basis van HelloFresh recepten.

## Features
- Scrapen van HelloFresh weekmenu
- Flexibele selectie van recepten
- Automatische generatie van boodschappenlijstjes
- Email functionaliteit met receptlinks

## Setup
1. Clone de repository
2. Maak een virtual environment: `python -m venv venv`
3. Activeer de virtual environment:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`
4. Installeer dependencies: `pip install -r requirements.txt`
5. Kopieer `.env.example` naar `.env` en vul de benodigde waardes in
6. Start de applicatie: `python src/app.py`

## Development
- Python 3.8+
- Flask framework
- BeautifulSoup4 voor scraping
- SQLite database

## License
MIT License