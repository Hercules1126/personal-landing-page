# Personal Landing Page — Python + Flask

A simple personal landing page built with Flask.

## Run locally

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python app.py
```

Open http://127.0.0.1:5000

## Personalize

Replace these image files in `static/images/`:
- `profile.jpg`
- `photo-1.jpg`
- `photo-2.jpg`
- `photo-3.jpg`

Then edit your name, links, and text in `templates/index.html`.

## Deploy

Push this project to GitHub and deploy it as a Render Web Service.

Build command:
`pip install -r requirements.txt`

Start command:
`gunicorn app:app`
