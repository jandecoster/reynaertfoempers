# 🦊 ReynaertRiders – Wielerclub Website

Officiële website van **ReynaertRiders**, een wielerclub uit de regio Gent.  
Gebouwd als een statische HTML/CSS/JS site — geen frameworks, geen build tools, gewoon openen en klaar.

---

## 📁 Projectstructuur

```
reynaertriders-website/
│
├── index.html        # Hoofdpagina (single-page met alle secties)
├── leden.html        # Ledenlijst pagina
├── sfeer.png         # Sfeerfoto (gebruikt in "Over ons")
└── README.md         # Dit bestand
```

---

## 📄 Pagina's & Secties

### `index.html` — Hoofdpagina
| Sectie | Beschrijving |
|---|---|
| **Hero** | Welkomstscherm met clubnaam, tagline en statistieken |
| **Over ons** | Clubgeschiedenis, waarden en sfeerfoto |
| **Fietsgroepen** | Overzicht van groepen A t.e.m. E met snelheid |
| **Kalender** | Aankomende ritten en het jaarlijkse hoofdevenement |
| **Routes** | Populaire fietsroutes met hoogteprofiel |
| **Word lid** | Call-to-action sectie |
| **Sponsors** | Partnerlogo's |
| **Contact** | Contactgegevens + contactformulier |

### `leden.html` — Ledenlijst
Overzicht van alle actieve leden voor het seizoen 2025.  
Huidige leden: Jan, Sam, Smalle, Spok, Wannes.

---

## 🎨 Design

| Eigenschap | Waarde |
|---|---|
| **Stijl** | Bold & sporty, donker thema |
| **Hoofdkleur** | Oranje `#F4420A` |
| **Achtergrond** | Zwart `#0D0D0D` |
| **Fonts** | Bebas Neue (titels) · Barlow (tekst) · Barlow Condensed (labels) |
| **Animaties** | CSS scroll-reveal + fade-up bij laden |
| **Responsive** | Ja — mobiel hamburger menu inbegrepen |

---

## ✏️ Iets aanpassen?

### Leden toevoegen
Open `leden.html` en voeg een nieuw kaartje toe in de ledenlijst:

```html
<div class="member-card">
  <div class="member-avatar">X</div>
  <div class="member-name">Naam</div>
  <div class="member-number">Lid #006</div>
</div>
```

### Sponsor toevoegen
Open `index.html`, zoek de sectie `id="sponsors"` en voeg toe:

```html
<a href="https://jouwsponsor.be" class="sponsor-card">
  <span>Sponsornaam</span>
</a>
```

### Evenement toevoegen
Zoek de sectie `id="kalender"` en voeg een event-item toe:

```html
<a class="event-item" href="#">
  <div class="event-date-box">
    <div class="day">15</div>
    <div class="month">jun</div>
  </div>
  <div>
    <div class="event-type">Wegrit</div>
    <div class="event-title">Naam van het evenement</div>
    <div class="event-meta">08:30 · Locatie</div>
  </div>
</a>
```

---

## 🚀 Hosting

De site is gehost via **Netlify**, gekoppeld aan deze GitHub repository.  
Elke push naar de `main` branch wordt automatisch live gezet.

| Platform | Link |
|---|---|
| GitHub | github.com/jandecoster/reynaertfoempers |
| Live site | reynaertfoempers.netlify.app |

---

## 📬 Contact

- **Club:** ReynaertRiders vzw
- **E-mail:** info@reynaertriders.be
- **Facebook:** [ReynaertRiders](https://facebook.com)
- **Instagram:** [@reynaertriders](https://instagram.com)
- **Strava:** [ReynaertRiders](https://strava.com)

---

*Gebouwd met ❤️ voor de ReynaertRiders — samen fietsen, samen genieten. 🚴*
