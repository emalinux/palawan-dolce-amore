# Palawan Dolce Amore Tribe Association – Hugo site

[![Netlify Status](https://api.netlify.com/api/v1/badges/dd411da4-0b54-42c9-bbbf-2e7d74d256be/deploy-status)](https://app.netlify.com/projects/timely-pasca-657021/deploys)

Sito statico realizzato con **Hugo** per raccontare le attività
dell’associazione *Palawan “Dolce Amore” Tribe Association*.

## 🧑‍💻 Autore

**Il progetto è stato sviluppato come lavoro pro bono**
Realizzato con ❤️ da [Manuel – Assembler Computer](https://www.assemblercomputer.net/)

Contatti diretti? [📧 emalinux77@gmail.com](mailto:emalinux77@gmail.com)

---

## Stack & requisiti

- **Static site generator:** Hugo (versione extended consigliata)
- **Linguaggi:** HTML, CSS, Go templates
- **Multilingua:** Inglese (default) + Italiano
- **Dipendenze esterne:**
  - [GLightbox](https://github.com/mcstudios/glightbox) per le gallerie
  - YouTube per i video (embed / link esterni)

Per avviare il progetto in locale:

```bash
hugo server -D

---

## Struttura principale


palawan/
├── config.yaml                # Configurazione Hugo e lingue
├── content/
│   ├── _index.md              # Home EN
│   ├── about/
│   ├── contact/
│   ├── donate/
│   ├── press/
│   ├── projects/
│   │   ├── 2019/
│   │   ├── 2020/
│   │   ├── 2021/
│   │   ├── 2022/
│   │   ├── 2023/
│   │   ├── 2024/
│   │   └── 2025/
│   ├── videos/
│   └── it/
│       ├── _index.md          # Home IT
│       ├── about/
│       ├── contact/
│       ├── donate/
│       ├── press/
│       ├── projects/
│       └── videos/
├── layouts/
│   ├── _default/
│   │   ├── baseof.html        # Layout principale (header, footer, ecc.)
│   │   └── single.html
│   ├── partials/
│   │   ├── header.html        # Titolo + menu + bandierine
│   │   └── page-hero.html     # Logo sopra le pagine interne
│   └── projects/              # Template per anni e lista progetti
├── static/
│   ├── css/
│   │   └── palawan.css        # Stili principali
│   ├── images/
│   │   ├── logok.png          # Logo hero
│   │   ├── home/              # Background card homepage
│   │   ├── press/             # Ritagli giornali
│   │   └── flags/             # uk.png / it.png
│   └── ...
└── README.md
