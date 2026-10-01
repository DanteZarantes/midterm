WEB Technologies 1 (Front End) — Midterm Project Report

Project: Nomad Trails Expedition Co.


1. Team Members and Contribution

This project was done individually. One student built the whole website.

  Full name: [YOUR FULL NAME]
  Contribution: 100% — planned the idea and style, built both pages (index.html
  and trips.html), wrote all HTML and CSS, chose the color palette and fonts,
  built the CSS Grid section and the pricing table, and wrote this report.

(If you submit as a team, replace this section with every member and what each
person built. A student who does not defend receives 0, even if the team
submitted.)


2. Topic of the Website and Why

Topic: a small brand website for a guided wilderness expedition company that
runs small-group treks, safaris and summit climbs.

Why this topic was chosen:
  - It gives a clear, single visitor in mind: someone who wants to book a guided
    trip and needs to compare options and prices.
  - It naturally needs the required elements — a form (contact and booking),
    a table (season departures and pricing), image cards, and clear sections.
  - The subject is visual, so it supports a strong hero, an earthy palette and
    a calm, outdoorsy style instead of a generic template look.


3. Style of the Website — Colors, Fonts and Main Elements

Colors (earthy expedition palette, kept the same on both pages):
  - Forest green  #2f4a3c  — headings and table header
  - Moss green    #6b8f5e  — accents, card borders, easy difficulty
  - Sand          #e9e2d0  — light backgrounds, navbar, cards
  - Clay orange   #c8703f  — buttons and call-to-action highlights
  - Ink           #23281f  — body text and footer background

Fonts:
  - Georgia (serif) for body and headings — gives a warm, editorial, journal
    feel that fits travel and storytelling.
  - Arial (sans-serif) for small labels, badges and table headers — keeps small
    uppercase text crisp and readable.

Main elements and why they were chosen:
  - Bootstrap navbar: one consistent, collapsible navigation on every page so
    the site works as one and is usable on small screens.
  - Full-bleed hero with a dark gradient over a photo: sets the mood and makes
    the first screen memorable at every size.
  - Hand-built CSS Grid "Featured Trails" section: shows custom CSS Grid and my
    own media queries (1 column on phones, 2 on tablets, 3 on desktop) rather
    than relying only on Bootstrap.
  - Pricing table (Trips page): a semantic table with thead, tbody and tfoot,
    row headers (scope), and colored difficulty badges — this is the required
    table and the main content of page 2.
  - Bootstrap grid cards ("What Every Price Includes" and "How It Works"): show
    correct use of the Bootstrap grid and components.
  - Accordion (FAQ) and two forms (contact + booking): required form usage plus
    a Bootstrap interactive component. Both forms use proper labels.
  - Shared footer on both pages for consistency.


4. Pages

  Page 1 — index.html (Home)
    Hero, Featured Trails (custom CSS Grid), How It Works (Bootstrap grid +
    ordered list), FAQ (Bootstrap accordion), Contact (form + details), footer.

  Page 2 — trips.html (Trips & Pricing)
    Hero, Season Departures & Pricing (semantic table), What Every Price
    Includes (Bootstrap grid cards), Reserve a Departure (form with labels and
    a select), footer.


5. Requirements Coverage (self-check)

  - Size: 2 pages for 1 student — met (index.html + trips.html).
  - Semantic HTML: header, nav, section, article, footer, table with thead/
    tbody/tfoot and scope — met.
  - At least 1 form: contact form (page 1) and booking form (page 2), both with
    labels — met.
  - At least 1 table: pricing table on page 2 — met.
  - Flexbox / Grid: custom CSS Grid trails section; Bootstrap grid rows — met.
  - Own media queries: custom @media at 768px and 992px in style.css — met.
  - Bootstrap: navbar, grid, accordion, forms, buttons — met.
  - Works: one navigation on every page, same style on all pages, no horizontal
    scroll at 375px, 768px and 1280px — met.


6. Screenshots

Add screenshots of every page at each screen size before submitting:

  index.html  — 375px:  [screenshot]
  index.html  — 768px:  [screenshot]
  index.html  — 1280px: [screenshot]
  trips.html  — 375px:  [screenshot]
  trips.html  — 768px:  [screenshot]
  trips.html  — 1280px: [screenshot]

(To capture: open each page, press F12, use the device toolbar, set the width,
and take a screenshot. Make sure the text in the screenshots is readable.)


7. Credits

  - Photos: Unsplash (https://unsplash.com) — free-to-use images, credited in
    the site footer on every page.
  - Framework: Bootstrap 5.3.3 (https://getbootstrap.com).
  - Fonts: system fonts (Georgia, Arial); no third-party font files used.

  All layout, custom CSS and written text are my own work.


8. Conclusion

I built a two-page brand website for a guided expedition company with a
consistent earthy style, one shared navigation and footer, a custom CSS Grid
section and a semantic pricing table. I practiced combining Bootstrap components
with my own CSS and media queries, keeping a single color and type system across
pages, and making every layout hold up from 375px to 1280px without horizontal
scroll. The main things I learned were how to mix a CSS framework with custom
styling cleanly and how to keep a multi-page site feeling like one product.


9. Links (required — submission without both links receives a grade of 0)

  GitHub repository URL: [PASTE YOUR REPOSITORY URL]
  Deployed website link (GitHub Pages): [PASTE YOUR GITHUB PAGES URL]


Note: for the actual submission the rules require this report as a .docx or .pdf
file named Midterm_FullName1_FullName2....docx (or .pdf). This .md file is the
plain-text content — copy it into that document before submitting.
