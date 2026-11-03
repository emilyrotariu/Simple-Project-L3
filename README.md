# README - Pagina Web Simplă cu Aplicații Meteo

## 📋 Descriere

Acest proiect reprezintă o pagină web simplă construită cu **HTML5** și **CSS3**, care include o structură de bază (header, navigație, secțiuni de conținut, footer) și un set complet de stiluri pentru o **aplicație meteo** (containere, formulare de căutare, prognoză pe zile și pe ore).

Fișierul HTML oferă scheletul paginii, iar fișierul CSS (`styles.css`) conține atât stilurile de bază pentru layout, cât și stilurile dedicate componentelor meteo și galeriei de imagini.

---

## 🗂️ Structura proiectului

```
├── index.html      # Structura paginii (header, main, footer, galerie)
└── styles.css      # Stiluri pentru layout, aplicații meteo și galerie
```

---

## 🚀 Funcționalități

### Structura HTML
- **Header** cu titlu și meniu de navigație (Home, About, Contact)
- **Main** cu trei secțiuni de conținut (`#home`, `#about`, `#contact`)
- **Secțiune galerie** (`#galerie`) cu un grid de 3 imagini (placeholder)
- **Footer** cu drepturi de autor

### Stiluri CSS
- **Reset global** pentru margini, padding și `box-sizing`
- **Design responsive** pentru mobil (breakpoint la `768px` și `600px`)
- **Meniu de navigație** orizontal cu efect hover (fundal portocaliu)
- **Card-uri de secțiune** cu umbră și colțuri rotunjite

### Componente pentru aplicații meteo
- **`.weather-container`** — container principal cu gradient mov-albastru
- **`.weather-app-box`** — cutii pentru fiecare aplicație meteo, cu efect hover (ridicare)
- **`.input-group`** — câmpuri de introducere + butoane, cu layout flexibil
- **`.weather-data`** — afișarea datelor meteo cu bordură colorată
- **`.loading`** — animație „pulse" pentru starea de încărcare
- **`.error`** — stil pentru mesaje de eroare (roșu)
- **`.forecast-grid`** — grilă responsive pentru prognoza pe zile
- **`.hourly-grid`** — grilă cu scroll vertical pentru prognoza pe ore

### Galerie de imagini
- Grid cu **3 coloane** pe desktop
- Se transformă într-o **singură coloană** pe ecrane sub `600px`

---

## 🛠️ Tehnologii folosite

- **HTML5** — structură semantică (`header`, `nav`, `main`, `section`, `footer`)
- **CSS3** — Flexbox, CSS Grid, gradienturi, animații (`@keyframes`), media queries, tranziții

---

## 📦 Instalare și utilizare

1. Clonează sau descarcă proiectul.
2. Asigură-te că fișierul `styles.css` se află în același director cu `index.html`.
3. Deschide `index.html` într-un browser modern (Chrome, Firefox, Edge, Safari).

> ⚠️ **Notă:** Secțiunea meteo este prezentă doar la nivel de stiluri CSS. Pentru funcționalitate reală (preluarea datelor meteo), este necesară adăugarea unui script JavaScript și conectarea la un API meteo (ex. OpenWeatherMap).

---

## 🎨 Personalizare

- **Culori principale:** `#35424a` (antet/footer), `#e8491d` (hover meniu), `#667eea` → `#764ba2` (gradient meteo)
- **Fonturi:** `Arial, sans-serif`
- **Breakpoints responsive:** `768px` și `600px`

Poți modifica cu ușurință variabilele de culoare și dimensiunile direct în `styles.css`.

---

## 📱 Responsive Design

| Dispozitiv | Comportament |
|-----------|--------------|
| Desktop (> 768px) | Layout complet, grid meteo pe mai multe coloane, galerie pe 3 coloane |
| Tabletă (≤ 768px) | Formularele meteo trec pe verticală, grid-urile se rearanjează |
| Mobil (≤ 600px) | Galeria devine o singură coloană |

---

## 📄 Licență

Acest proiect este destinat uzului educațional și poate fi modificat liber. © 2025 My Simple Webpage. Toate drepturile rezervate.