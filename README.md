
## Project structure

```
abinacharya.github.io/
├── _config.yml             # ★ Site title, tagline, theme colors, social links
├── _data/
│   └── navigation.yml      # ★ The top navigation menu
├── index.md                # Home page (hero image + intro + socials)
├── _pages/
│   ├── about.md            # About me
│   ├── education.md        # Degrees + honors & awards
│   ├── research.md         # Research overview
│   ├── projects.md         # Project entries
│   ├── experience.md       # Work / teaching experience
│   ├── skills.md           # Skill categories
│   └── resume.md           # Embedded + downloadable resume PDF
├── assets/
│   ├── images/
│   │   └── home.svg        
│   └── docs/
│       └── Abin_Acharya_Resume.pdf
├── Gemfile                 
└── README.md
```

## Where to change things

| What | Where |
|---|---|
| Site title, tagline, your name | `_config.yml` (top section) |
| Theme colors | `_config.yml` → `minimal_mistakes_skin` (try "air", "mint", "dark"…) |
| Social links (footer, every page) | `_config.yml` → `footer: links:` |
| Navigation menu | `_data/navigation.yml` |
| Hero image | `assets/images/` + one line in `index.md` (see below) |
| Intro text | `index.md` and `_pages/about.md` |
| Degrees / awards | `_pages/education.md` |
| Research description | `_pages/research.md` |
| Projects | `_pages/projects.md` — copy a `###` block to add one |
| Jobs | `_pages/experience.md` — same pattern |
| Skills | `_pages/skills.md` |
| Resume | replace `assets/docs/Abin_Acharya_Resume.pdf` (keep the same name) |
| Add a page | copy any file in `_pages/`, change its `title` and `permalink`, add it to `_data/navigation.yml` |








