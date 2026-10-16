# Kavinė Koralai — svetainės demonstracija

> Vieno failo demo svetainė Karoliniškių kavinei „Koralai“ (lietuvių kalba).

> Dalis portfolio: [svetainė-portfolio](https://auryxn.github.io) — svetainės
> repozitorija [site-admin](https://github.com/auryxn/site-admin).

## Kas tai

Kavinė Koralai — tai **vieno failo (`index.html`) demo svetainė** mažai karoliniškių
kavinei, kuri šiandien neturi savo puslapio internete. Tai vizualus pavyzdys, kaip
verslas galėtų atrodyti internete: dienos meniu, virtuvės galerija, banketų
užsakymai ir kontaktai su mygtuku „Skambinti“.

Puslapis parašytas lietuviškai (`lang="lt"`), o poraštėje tiesiog parašyta, kad
puslapis yra **demonstracija**. Ši svetainė – Kavinės Koralai prekinis ženklas, o
techniškai ją atitinka tos pačios architektūros [Velora Café](https://github.com/auryxn/velora-cafe)
svetainė su redaguojama administravimo panele.

## Ką rasite puslapyje

- **Navigacija** su inkarinėmis nuorodomis ir CTA mygtuku.
- **Hero** – „Jauki namų virtuvė Karoliniškėse“: trumpas aprašymas, reitingas,
  darbo laikas.
- **Šiandienos meniu** (`#menu`) – dienos patiekalai ir kainos.
- **Apie** (`#about`) – „Nuo 2008 metų maitiname Karoliniškes“.
- **Galerija** (`#gallery`) – virtuvės/kavinės nuotraukos.
- **Banketai** (`#banquet`) – švenčių ir banketų organizavimas.
- **Kontaktai** (`#contact`) – telefonas, adresas (V. Maciulevičiaus g. 51,
  Vilnius), darbo laikas, Facebook.
- **CTA** – „Atverkite duris internetu“ su skambučio mygtuku.

## Technologijos

- Vienas **`index.html`** failas: žymėjimas + stiliai (`<style>`) + skriptai.
- Šriftai iš Google Fonts (Playfair Display, Inter).
- Jokių karkasų, „build“ žingsnio ar priklausomybių.

## Paleidimas

Tiesiog atidarykite `index.html` naršyklėje.

Arba paleiskite lokalų serverį:

```bash
python3 -m http.server 8000
# tada http://localhost:8000
```

## Struktūra

```
kavine-koralai/
└─ index.html      # visas puslapis (žymėjimas + stiliai + skriptai)
```

## Būsena

**Demo maketas (paruoštas kaip vizualus pavyzdys).** Data: 2026-10-16.
