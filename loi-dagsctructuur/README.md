# LOI Dagstructuur – Website

## Lokaal testen

```bash
pip install -r requirements.txt
python app.py
```
Open dan: http://localhost:5000

---

## Deployen op Render (gratis)

### Stap 1 – GitHub repo aanmaken
1. Ga naar [github.com](https://github.com) → **New repository**
2. Naam: `loi-dagstructuur`
3. Zet op **Public**
4. Klik **Create repository**

### Stap 2 – Bestanden uploaden
Upload deze bestanden naar de repo:
- `index.html`
- `app.py`
- `requirements.txt`
- `render.yaml`

Via GitHub website: klik **Add file → Upload files**

### Stap 3 – Render koppelen
1. Ga naar [render.com](https://render.com) → gratis account aanmaken
2. Klik **New → Web Service**
3. Koppel je GitHub account
4. Selecteer de `loi-dagstructuur` repo
5. Render detecteert `render.yaml` automatisch
6. Klik **Create Web Service**

Je site is live op: `https://loi-dagstructuur.onrender.com`

---

## Bestanden
| Bestand | Functie |
|---|---|
| `index.html` | De website zelf |
| `app.py` | Flask server |
| `requirements.txt` | Python packages |
| `render.yaml` | Render configuratie |
