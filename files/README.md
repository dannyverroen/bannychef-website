# Bannychef Website

Statische onepager voor [bannychef.nl](https://bannychef.nl).

## Structuur

```
bannychef-website/
├── index.html          — de volledige website
├── assets/             — zet hier alle afbeeldingen neer
│   ├── logo-black.png  — logo zwart (uit BrandDeck)
│   ├── logo-white.png  — logo wit (uit BrandDeck)
│   ├── groenten.png    — illustratie alle groenten (uit BrandDeck)
│   ├── aubergine.svg
│   ├── bonen.svg
│   ├── broccoli.svg
│   ├── champignon.svg
│   ├── garnaal.svg
│   ├── kip.svg
│   ├── pompoen.svg
│   ├── soeppan.svg
│   ├── tomaat.svg
│   ├── ui.svg
│   ├── vis.svg
│   └── wok.svg
└── README.md
```

## Assets downloaden uit BrandDeck

Ga naar [my.banny.studio](https://my.banny.studio) en open het Banny Chef merk.
Download de bestanden onder Logo's en Illustraties en zet ze in de `assets/` map.

Bestandsnamen die je nodig hebt:
- Logo zwart PNG → opslaan als `logo-black.png`
- Logo wit PNG → opslaan als `logo-white.png`
- `banny_chef_with_all_vegetables.png` → opslaan als `groenten.png`
- Alle SVG illustraties → opslaan met de naam zoals hierboven

## Live zetten via GitHub Pages

1. Maak een nieuwe repository aan op GitHub, bijv. `bannychef-website`
2. Push deze map:
   ```bash
   git init
   git add .
   git commit -m "Eerste versie website"
   git remote add origin https://github.com/dannyverroen/bannychef-website.git
   git push -u origin main
   ```
3. Ga naar Settings → Pages → Source: `main` branch → `/root`
4. De site is live op `https://dannyverroen.github.io/bannychef-website`

## Eigen domein koppelen

Wil je de website op een eigen domein zoals `www.bannychef.nl` zetten:
1. Voeg een `CNAME` bestand toe met daarin `www.bannychef.nl`
2. Stel bij je domeinregistrar een CNAME record in: `www` → `dannyverroen.github.io`

## Aanpassingen

Geef het gewoon aan in de chat, dan pas ik `index.html` aan en push ik de wijziging.
