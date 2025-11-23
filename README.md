# Palawan Dolce Amore Tribe Association – Hugo site

Sito statico realizzato con **Hugo** per raccontare le attività
dell’associazione *Palawan “Dolce Amore” Tribe Association*.

Il progetto è stato sviluppato come lavoro pro bono
da **Manuel – Assembler Computer** con supporto tecnico “Manuel & friends”.

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