
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

## Add your gif to the home page

1. Copy your gif into `assets/images/` and rename it **home.gif**
2. Open `index.md`. Delete the `![home](/assets/images/home.svg)` line and
   uncomment the `home.gif` line below it (remove the `<!--` and `-->`).
3. Commit and push — done.

## Deploy to GitHub Pages

Your GitHub username must be `abinacharya` for the site to live at
`https://abinacharya.github.io`. (If your username is different, name the
repo `<username>.github.io` and the site lives at that URL instead.)

### 1. Create the repository
1. Go to https://github.com/new
2. Repository name: **abinacharya.github.io** (exactly)
3. Visibility: **Public**
4. Don't initialize with a README — click **Create repository**

### 2. Upload the source code



### 4. Visit your site
After the first build finishes (1–3 minutes):

**https://abinacharya.github.io**

Every future `git push` to `main` rebuilds and redeploys automatically.

## Preview locally (optional)

GitHub builds the site for you, so this is never required. If you want a
live preview while editing: install Ruby, then

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

and open http://localhost:4000.
