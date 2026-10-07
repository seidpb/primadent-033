# PrimaDent 033 – landing stranica

Probna landing stranica za Stomatološku ordinaciju PrimaDent 033, Priboj.

## Struktura
```
index.html      cela stranica (fontovi, logo i naslovna slika ugrađeni)
slike/          fotografije tretmana, Instagram mreža, logo
.nojekyll       isključuje Jekyll na GitHub Pages
```

## Pokretanje lokalno
Otvorite `index.html` preko lokalnog servera (zbog slika iz `slike/`):
```
npx serve .
# ili
python3 -m http.server
```

## Objavljivanje na GitHub
```
git init
git add .
git commit -m "PrimaDent 033 landing"
git branch -M main
git remote add origin https://github.com/<korisnik>/primadent033.git
git push -u origin main
```
Zatim: Settings → Pages → Source: **Deploy from a branch**, `main`, `/ (root)` → Save.
Stranica će biti na `https://<korisnik>.github.io/primadent033/`.

## Zamena slika
Fajlove u `slike/` možete zameniti svojim fotografijama pod istim imenom.

## Napomene
- Stock fotografije su sa Unsplash i Pexels; potpisi autora ostaju na slikama.
- Usluge, tretmani i tekst "O nama" su probni – proveriti sa ordinacijom pre objave.
