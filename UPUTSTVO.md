# Joy at Sea – Website

## Struktura fajlova

```
joy-at-sea/
├── index.html          ← Početna stranica
├── shop.html           ← Galerija/Shop stranica
├── about.html          ← O nama stranica
├── css/
│   └── style.css       ← Svi stilovi
├── js/
│   └── main.js         ← Sve animacije i interakcije
└── images/             ← OVDE stavi svoje slike (prazno)
```

---

## Kako ubaciti slike

### 1. Pozadinske slike sekcija
U svakoj sekciji postoji komentar koji ti govori šta da zameniš.
Primer za hero sekciju:
```html
<!-- Zameni div.hero-bg-placeholder sa: -->
<style>
  .hero { background-image: url('images/hero-bg.jpg'); }
</style>
```

### 2. Korica knjige
U `index.html` pronađi `.book-cover-placeholder` i zameni sa:
```html
<img class="book-cover-img" src="images/cover.jpg" alt="Joy at Sea Cover">
```

### 3. Slike proizvoda (shop.html)
Zameni `.product-img-placeholder` div sa:
```html
<img class="product-img" src="images/product1.jpg" alt="Naziv knjige">
```

### 4. Amazon linkovi
Svugde gde piše `YOUR_AMAZON_LINK_HERE` zameni sa tvojim Amazon linkom.

---

## Kako ubaciti na hosting

### Opcija A – cPanel Hosting (najčešće)
1. Uloguj se na cPanel svog hostinga
2. Klikni na **File Manager**
3. Otvori folder `public_html`
4. Klikni **Upload** (gore desno)
5. Otpremi sve fajlove: `index.html`, `shop.html`, `about.html`
6. Otpremi folder `css/` sa fajlom `style.css` unutra
7. Otpremi folder `js/` sa fajlom `main.js` unutra
8. Otpremi folder `images/` sa svim tvojim slikama
9. Tvoj sajt je živ! Poseti svoj domen.

### Opcija B – FTP (FileZilla)
1. Skini FileZilla besplatno: https://filezilla-project.org
2. Konektuj se sa FTP podacima od hostinga (host, user, pass, port 21)
3. S desne strane navigiraj do `public_html`
4. S leve strane otvori folder `joy-at-sea` na svom računaru
5. Selektuj sve fajlove i foldere i prevuci na desnu stranu
6. Sačekaj da se otpremi – gotovo!

### Opcija C – Netlify Drop (besplatno, najlakše!)
1. Idi na: https://app.netlify.com/drop
2. Prevuci i pusti ceo `joy-at-sea` folder na stranicu
3. Dobijaš link za par sekundi – bez plaćanja!

---

## Izmena teksta
- Svi "Lorem ipsum" tekstovi su placeholder – zameni ih tvojim pravim tekstovima
- Svi kontakt podaci (email, telefon, lokacija) su placeholder – zameni ih
- Linkovi na socijalnim mrežama (`href="#"`) – zameni sa tvojim pravim linkovima

## Font
Sajt koristi **Caveat** font (Google Fonts) koji je najbliži rukopisnom fontu sa slike.
Font se učitava automatski sa interneta – nema potrebe za ručnim preuzimanjem.

---

Srećno! 🚢
