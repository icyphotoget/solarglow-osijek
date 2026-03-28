# SolarGlow Osijek - Web stranica

Profesionalna web stranica za tvrtku koja se bavi pranjem solarnih panela u Osijeku i okolici.

## 🚀 Kako pokrenuti

### Opcija 1: Direktno otvaranje (najjednostavnija)
1. Otvorite `index.html` u vašem web pregledniku
2. Stranica će se prikazati

### Opcija 2: Local Development Server
Koristite Python simple HTTP server:

```bash
# Windows
cd solarglow-osijek
python -m http.server 8000
# ili
py -m http.server 8000

# macOS/Linux
cd solarglow-osijek
python3 -m http.server 8000
```

 zatim otvorite `http://localhost:8000` u pregledniku.

### Opcija 3: VS Code Live Server
1. Otvorite folder u VS Code
2. Instalirajte "Live Server" ekstenziju
3. Desni klik na `index.html` → "Open with Live Server"

### Opcija 4: Deploy na Vercel/Netlify
1. Pushajte na GitHub repo
2. Povežite s Vercel ili Netlify
3. Automatski će se deployati

---

## 📁 Struktura projekta

```
solarglow-osijek/
├── index.html          # Glavna HTML stranica
├── README.md           # Ova datoteka
└── assets/
    ├── css/
    │   └── style.css  # Prilagođeni stilovi
    ├── js/
    │   └── main.js    # JavaScript interakcije
    └── img/           # Slike (placeholder - dodati vlastite)
```

---

## ✨ Značajke

- [x] Responsive dizajn (mobile-first)
- [x] Mobile navigacija s hamburger menu-om
- [x] Hero sekcija s animacijama
- [x] Problem/Rješenje sekcija
- [x] Cjenik s 3 paketa
- [x] Lokalni SEO s mikrolokacijama
- [x] Kontakt forma s validacijom
- [x] Smooth scroll navigacija
- [x] Lucide ikone
- [x] Tailwind CSS CDN

---

## 🎨 Tehnologije

- **HTML5** - Struktura stranice
- **Tailwind CSS** (CDN) - Brzi CSS framework
- **Vanilla JavaScript** - Interakcije bez ovisnosti
- **Lucide Icons** - Moderne ikone
- **Google Fonts (Inter)** - Tipografija

---

## 📝 Popis za prilagodbu

Prije nego što stranica bude spremna za produkciju, potrebno je:

### 1. Kontakt podaci
- [ ] Dodajte stvarni telefonski broj umjesto `09X XXX XXXX`
- [ ] Dodajte email adresu
- [ ] Dodajte web stranicu (ako postoji)

### 2. Slike
- [ ] Zamijenite placeholder slike stvarnim fotografijama
- [ ] Dodajte sliku hero sekcije (solarni paneli)
- [ ] Dodajte slike za svaku uslugu
- [ ] Dodajte mapu područja servisiranja

### 3. Statistika
- [ ] Ažurirajte broj očišćenih panela (500+)
- [ ] Ažurirajte ocjenu kupaca (5.0)
- [ ] Ažurirajte broj zadovoljnih klijenata

### 4. Forma
- [ ] Povežite formu s backendom ili email servisom
- [ ] Dodajte privacy policy link
- [ ] Dodajte GDPR privolu

### 5. SEO
- [ ] Dodajte Google Analytics
- [ ] Dodajte Google Search Console
- [ ] Dodajte favicon
- [ ] Dodajte Open Graph sliku

---

## 🔧 Dodatne prilagodbe

### Promjena boja
Boje su definirane u Tailwind config sekciji `index.html`:
```javascript
colors: {
    'solar-blue': '#1A365D',
    'solar-yellow': '#F6AD55',
    'solar-orange': '#ED8936',
}
```

### Dodavanje nove sekcije
Kopirajte postojeću sekciju i prilagodite sadržaj.

### Promjena fontova
Trenutno se koristi Google Font "Inter". Za promjenu, zamijenite link u `<head>` sekciji.

---

## 📞 Podrška

Za pitanja o kodu ili prilagodbi, javite se.

---

## 📄 Licenca

Ova web stranica je vlasništvo tvrtke SolarGlow Osijek.
Izrada: DECKART

© 2026 SolarGlow Osijek. Sva prava pridržana.
