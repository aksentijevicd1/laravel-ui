# Online Kviz - Frontend

## Opis

Ova aplikacija je veb platforma za igranje online kvizova. Korisnici mogu igrati kvizove u privatnim i javnim sobama. Administratori imaju mogućnost kreiranja sopstvenih soba. Poeni se dodeljuju na osnovu tačnosti i brzine odgovora. Uz pomoć soketa omogućen je uvid u broj korisnika koji su već odgovorili na pitanje i onih koji još uvek razmišljaju.

## Tehnologije

- **Frontend:** React
- **Backend:** Laravel (pogledajte zaseban `README.md` u backend repozitorijumu)
- **Alati:** HTML, CSS, JavaScript

## Instalacija

1. **Kloniranje repozitorijuma:**

   ```bash
   git clone https://github.com/elab-development/internet-tehnologije-projekat-onlinekviz_2020_0168.git
   cd internet-tehnologije-projekat-onlinekviz_2020_0168
   ```

2. **Navigacija do frontend foldera:**

   ```bash
   cd frontend
   ```

3. **Instalacija zavisnosti:**

   Uverite se da imate instaliran Node.js i npm. Zatim pokrenite:

   ```bash
   npm install
   ```

## Pokretanje projekta

Pokrenite lokalni razvojni server:

```bash
npm start
```

Aplikacija će biti dostupna na `http://localhost:3000`.

## Funkcionalnosti

1. **Početna stranica:**
   - Korisnici mogu da se prijave ili registruju kako bi mogli da istraže dostupne kvizove i učestvuju u njima.

2. **Stranica za registraciju:**
   - Korisnici mogu da kreiraju nalog unosom svog imena, mejl adrese i lozinke.
   
3. **Stranica za prijavu:**
   - Korisnici mogu da se prijave na sistem unosom mejl adrese i lozinke.

4. **Stranica za resetovanje lozinke:**
   - Korisnici mogu da resetuju svoju lozinku putem mejla.

5. **Kreiranje kviza:**
   - Administratori mogu da kreiraju nove kvizove sa pitanjima i odgovorima.

6. **Igranje kviza:**
   - Korisnici mogu da učestvuju u kvizovima, odgovaraju na pitanja i dobijaju poene na osnovu tačnosti i brzine.

7. **Stranica sa rezultatima:**
   - Korisnici mogu da vide rezultate drugih korisnika nakon završetka kviza.

## API Dokumentacija

API dokumentacija se može naći u PDF dokumentu "ITEH dokumentacija.pdf" ili u sekciji `api.php` Laravel aplikacije.
