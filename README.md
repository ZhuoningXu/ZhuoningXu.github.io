# ZhuoningXu.github.io

Personal academic website of **Zhuoning (Johnny) XU** — MS in Computer Science at
NYU Courant. Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
Jekyll template and hosted on GitHub Pages.

**Live site:** https://ZhuoningXu.github.io

## How content is organized

| What | Where |
|------|-------|
| Site-wide settings (name, bio, social links, site URL) | `_config.yml` |
| Top navigation menu | `_data/navigation.yml` |
| Home / About page | `_pages/about.md` |
| Publications (one file per paper) | `_publications/` |
| Projects (one file per project) | `_portfolio/` |
| CV page | `_pages/cv.md` |
| Downloadable PDFs (CV, slides) | `files/` |
| Images (profile photo, figures) | `images/` |

## Editing

You can edit any `.md` / `.yml` file directly on github.com (pencil icon) or locally
with Git / GitHub Desktop. Each push to `main` triggers an automatic rebuild — the live
site updates within a couple of minutes.

To add a profile photo: drop `images/profile.png` into the repo and set
`avatar: "profile.png"` under `author:` in `_config.yml`.
