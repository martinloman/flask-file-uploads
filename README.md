# Flask File Upload Demo

Detta projekt visar hur man hanterar filuppladdningar med Flask och ett HTML-formulär.

## Funktioner
- Ladda upp filer via ett webbformulär
- Filer sparas i mappen `uploads`
- Flash-meddelanden visar status för uppladdning
- `.gitignore` exkluderar uppladdade filer från versionshantering

## Kom igång

1. Installera beroenden:
   ```cmd
pip install -r requirements.txt
   ```
   eller
   ```cmd
py -m pip install -r requirements.txt
   ```
2. Starta servern:
   ```cmd
python app.py
   ```cmd
   eller 
   ```
py app.py
   ```
3. Öppna webbläsaren och gå till `http://localhost:5000`

## Mappstruktur
```
flask-file-uploads/
├── app.py
├── requirements.txt
├── uploads/
│   └── .gitkeep
├── templates/
│   └── upload.html
├── .gitignore
└── README.md
```

## Noteringar
- Endast vissa filtyper tillåts (se `ALLOWED_EXTENSIONS` i `app.py`).
- Mappen `uploads` är ignorerad av Git förutom `.gitkeep`-filen.

