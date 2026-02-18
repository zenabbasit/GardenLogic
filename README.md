Garden Logic is a web app that helps users choose plants that actually work for their garden.  
It recommends plants based on location (hardiness zone), sunlight, soil type, plant preferences, season, and how much space is available.

The goal was to make plant selection easier by combining real gardening data with a simple rule-based decision system. The app filters through a custom plant database and suggests options that fit both the user’s environment and garden size.

## What it does

- Matches plants to your city’s hardiness zone  
- Filters by sunlight, soil type, plant type, and season  
- Chooses plants that fit within your garden’s dimensions  
- Uses a rule-based selection algorithm  
- Simple web interface built with Flask  

## Tech used

- Python  
- Flask  
- Pandas  
- HTML/CSS  
- CSV datasets (plants + cities)

## How to run

```bash
pip install flask pandas
python app.py
