# yibinfan.cc Personal Academic Website

This directory is a starter structure for using `yibinfan.cc` as a polished personal website for academic job search.

The site should do three jobs quickly:

1. Establish who Yibin Fan is and what kind of scholar they are.
2. Make research, publications, teaching, and CV easy for search committees to scan.
3. Feel current, careful, and professional without looking like a corporate portfolio.

## Recommended Structure

```text
yibinfan.cc/
  site/
    index.html
    pages/
      research.html
      teaching.html
      cv.html
      contact.html
    styles/
      base.css
    scripts/
      main.js
  content/
    profile.md
    research.md
    publications.md
    teaching.md
    job-market.md
    talks.md
    service.md
    contact.md
  assets/
    cv/
      yibin-fan-cv.pdf
    headshots/
    images/
  public/
    robots.txt
    favicon/
    _redirects
  docs/
    website-map.md
    design-system.md
    academic-job-search-content-checklist.md
    domain-dns-checklist.md
    launch-checklist.md
```

## Pages To Have

- **Home:** concise academic identity, research areas, selected work, teaching snapshot, contact.
- **Research:** politicization, online communities, platform migration, publications, working papers, methods.
- **Teaching:** courses taught and prepared, computational research workshop, mentoring.
- **CV:** linked PDF, education summary, last updated date.
- **Contact:** UW email, institutional affiliation, Google Scholar, ORCID, GitHub, LinkedIn.

## CV-Based Academic Identity

Yibin Fan is a PhD student in Communication at the University of Washington, with an expected graduation date of Spring 2027. His dissertation, "Everything to do with Politics: Examining Politicization in Online Communities," is advised by Benjamin Mako Hill, with Patricia Moy, Yuan Hsiao, and Christopher Adolph on the committee. He also has a Statistics Certificate.

The current site copy positions him around computational and political communication, online communities, incidental political discussion, politicization, platform migration, and digital public communication.

## Design Direction

Aim for a quiet editorial academic site: lots of whitespace, excellent typography, confident headings, restrained color, and clear page hierarchy. It should feel fresh because it is crisp and well-composed, not because it uses loud effects.

Good visual cues:

- A professional headshot in the first viewport.
- One accent color used sparingly for links and key calls to action.
- Short, scannable publication cards.
- A homepage that immediately tells visitors field, methods, and research contribution.
- Mobile-first layouts that still feel dense enough for faculty search committees.

## Hosting Recommendation

For a simple, elegant academic site:

- **Cloudflare Pages:** excellent if the domain will also be managed through Cloudflare.
- **GitHub Pages:** good if the site is simple HTML/CSS or static generated.
- **Vercel/Netlify:** good if later rebuilt with Astro, Next.js, or another framework.
