# abin-acharya.github.io

A small, self-contained Jekyll site — no theme, no gems to fight with. GitHub Pages builds it
automatically every time you push.

---

## 1. Putting it live

1. Open your `abin-acharya.github.io` repo locally (or in the GitHub web editor).
2. **Delete the old Minimal Mistakes files** — `_sass/`, `_pages/`, the old `_config.yml`,
   `Gemfile`, `index.md`, and any `_layouts`/`_includes` from the theme. Keep `.git/`.
3. Copy everything from this folder into the repo root.
4. Commit and push. Wait ~1 minute, then reload <https://abin-acharya.github.io>.

Before you push, do these three things:

- [ ] Save your headshot as `assets/img/profile.jpg` (square crop looks best).
      If it's missing the page shows your initials in a circle instead — nothing breaks.
- [ ] Save your CV as `assets/files/abin-acharya-cv.pdf`.
- [ ] Put your real Google Scholar URL in `_config.yml` (it's a placeholder right now).

Your old links keep working: `/about/` redirects to the home page, and `/education/`,
`/experience/`, `/skills/`, `/resume/` all redirect to `/cv/`.

---

## 2. Where everything lives

| I want to change… | Open this file |
|---|---|
| Name, role, advisor, email, social links, CV path | `_config.yml` |
| The menu at the top | `_data/nav.yml` |
| News items | `_data/news.yml` |
| Research interest tags on the home page | `_data/interests.yml` |
| Publications | `_data/publications.yml` |
| Projects | `_data/projects.yml` |
| Education, experience, awards, skills | `_data/cv.yml` |
| Your bio paragraphs | `index.html` |
| The research write-up | `research.html` |
| Colors, fonts, spacing | `assets/css/style.css` (all colors are at the top) |
| The header / footer, on every page at once | `_includes/header.html`, `_includes/footer.html` |

The rule of thumb: **lists of things live in `_data/*.yml`, prose lives in the `.html` page.**
You should almost never need to touch `_layouts/`.




