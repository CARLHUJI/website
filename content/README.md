# Content archive — old Wix site

Everything from <https://mikeklut.wixsite.com/carl>, captured 2026-09-24 as the source material for the redesign.
Images are in [`/assets/images`](../assets/images) (70 files, each with a caption in `README.md` / `manifest.json`).

## Pages (all 8 in the old site's sitemap)

| Old page | In old menu? | Saved as | What's in it |
|---|---|---|---|
| `/` Home | yes | `home.md` | Lab intro paragraph, 9 images |
| `/projects-1` Projects | yes | `projects.md` | 3 research projects (heterochromatin & aging in gametes; GASP / prolonged starvation; ancient beer yeast), 3 images |
| `/our-research` Our Research | **no** (hidden) | `our-research.md` | Chromatin / heterochromatin background text, 3 images |
| `/people` People | yes | `people.json` | 13 entries: name, position, email (PI and lab manager), photo |
| `/publications` Publications | yes | `publications.json` | 27 items (22 papers, 5 press items) with citation, year, link, thumbnail |
| `/news` News | **no** (hidden) | `news.json` | 4 posts from 2017–2018 |
| `/lab-photos` Lab Photos | yes | only images | 15 gallery photos with captions (see `assets/images/README.md`) |
| `/contact` Contact | yes | `contact.md` | Address, phones, emails, recruitment text, contact-form fields |
| (every page) | — | `site.json` | Site title, browser title, meta description, menu, header logos, footer |

## Verification

- Every line of text on all 8 pages was checked against these files. All are present except the two deliberate omissions listed below.
- All 70 unique images referenced by the 8 pages are downloaded at full resolution. None are missing.

## Things to decide during the redesign

- **Outdated content:** the footer says "© 2017", the news stops in 2018, and the hidden pages were never linked. Decide whether to refresh News or drop it.
- **Placeholder people:** People has two placeholder entries, "A" (PhD student) and "B" (MSc student), which share a stock photo.
- **Publication gaps:**
  - The two oldest papers (PNAS 2017, Cancer Research 2016) have no link or thumbnail on the old site.
  - The "Evolton" item links to a PLOS Biology article; confirm what it should say.
  - The list is only roughly chronological; the old site has some 2023 and 2024 items out of order.
- **Stray text (not archived):**
  - The publications page contains a biography of Björn Schumacher (another researcher), which looks like a leftover.
  - The news page has a template "Click Here" button linking to wix.com.
- **Emails:** the contact page lists both mikeklut@gmail.com and michaelk@ekmd.huji.ac.il.
- **Image rights:** several images are stock or third-party; they are flagged ⚠️ in `assets/images/README.md`.
