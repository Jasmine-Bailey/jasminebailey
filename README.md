# Miss Jasmine Bailey — Professional Portfolio Website

A single-file portfolio website for Jasmine P.R. Bailey (Native English Teacher, Kowloon, Hong Kong), built as her IB Educator Certificate professional portfolio (University of Windsor). Everything — pages, photos, lesson plan PDFs, fonts styling, decorative art — lives inside one `index.html` (~3.2 MB). No build step, no folders, no dependencies.

## Pages (8)

1. **Home** — intro, headshot, key stats, registration/clearance info, page links
2. **Teaching Philosophy** — 5 IB pillar cards, her quote, and the full philosophy shown open with her classroom photo
3. **Education & Experience** — teaching timeline (2006–present) and qualifications, worded with natural IB/PYP language (ATL, learner profile)
4. **Professional Development** — courses and certifications
5. **Lesson Portfolio** — curricula, programme highlights, clubs, digital tools, plus two embedded lesson plans (downloadable PDFs) and three captioned classroom photos
6. **Testimonials** — the "Board of Joy" photo + references card
7. **Goals** — Plan of Action graphic with her reflection text
8. **Gallery** — 8 captioned classroom photos in a two-column layout

## How to publish

The site is one file, so any static host works. Easiest options:

- **Netlify Drop** (netlify.com/drop) — drag `index.html` onto the page, done. Free, instant URL, can rename the site.
- **Tiiny.host** — same drag-and-drop idea.
- **GitHub Pages** — put `index.html` in a repo, enable Pages in settings.

Wix, Genially and Google Sites **cannot** import an HTML file — they only allow iframe embeds, which look bad. Use one of the hosts above instead.

## How to edit

Open `index.html` in any text editor and search for the text you want to change — all wording is plain HTML. Two things are intentionally left as placeholders for Jasmine to fill in:

- **Lesson Portfolio → Lesson plans**: each card has a "Reflection placeholder" — replace that paragraph with her actual reflection on the lesson.

To swap a photo, replace the long `src="data:image/webp;base64,..."` string on that `<img>` with a new base64 string (or a normal image URL if hosting more than one file).

## Notes

- **Student privacy**: children's faces are blurred throughout (Gallery photos 3, 4, 7, 8 and the photo-album shot in Lesson Portfolio). Photos 3 and 7 were blurred by Jasmine originally; 4, 8 and the album were blurred to match her style. Jasmine herself is visible in all photos. If new photos are added, blur student faces first.
- **Fact check**: the Goals text says "two decades of teaching" while the CV says 14+ years — left verbatim as provided; reconcile if needed.
- **Lesson plan downloads** are embedded in the page (no separate files needed) and save as "Lesson Plan 1 - Jasmine Bailey.pdf" and "The Magic Hotpot (S2W) - Jasmine Bailey.pdf".
- **Fonts** (DM Serif Display + Fira Sans) load from Google Fonts, so they need an internet connection; offline the site still works with fallback fonts.
- The source Google Drive folder used for content is shared "anyone with the link" — consider restricting it once the site is finalised.

## Credits

- Design adapted from the "Pastel Watercolor Brushstrokes" template by **Slidesgo** (attribution kept in the site footer — keep it there, it's a licence condition of the free template).
- Watercolor art elements are from that template, recoloured to the site's pink/sage/gold palette.