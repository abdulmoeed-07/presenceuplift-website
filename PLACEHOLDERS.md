# Website placeholders: what we need to fill

Every placeholder on the site has a yellow tag (PH-01, PH-02…) and a dashed border. Search `index.html` for the ID to find it.
**Don't merge to `main` (the live site) until the proof items (marked ★) are filled or the empty sections are removed.**

## Positioning (decide first, everything else depends on these)
| ID | What | Notes |
|---|---|---|
| PH-01 | Niche / who we serve | 1 niche, or at most 2–3 verticals. Shows as the hero eyebrow. |
| PH-02 | Specific promise + timeframe | Replaces "client magnet". Must be measurable. |
| PH-06 | Fit profiles + minimum fit (revenue/stage) | 3 draft profiles are already written, so rewrite them to match the niche. |
| PH-07 | Name of our method | e.g. "The ___ System™". Steps can stay. |
| PH-15 | Guarantee | Only one we can actually honour. Feeds FAQ answer in PH-21. |

## Proof ★
| ID | What | Format |
|---|---|---|
| PH-03 | One-line proof under hero CTA | e.g. "XX clients · XXM views · XX countries" |
| PH-05 | Client logos (6) | PNG/SVG, transparent background |
| PH-08 | 4 headline stats | Views, followers gained, brands managed, posts/month |
| PH-09–11 | 3 case studies | Client, industry, timeframe, 6 stats, before/after story, 3 best reels with view counts |
| PH-12 | Portfolio: 4 reels + 4 carousels/posts | MP4 / embed links / images |
| PH-13 | Video testimonial | 30–60 sec, client says name, business, result |
| PH-14 | 3 written testimonials | Quote with a number, name, role, business, headshot |

## Video
| ID | What | Format |
|---|---|---|
| PH-04 | Founder / authority video + 3 "you'll learn" points | 60–90 sec, YouTube/Vimeo/Loom link or MP4 |
| PH-20 | 4 video FAQs | 30–60 sec each, one question per video |

## Content
| ID | What |
|---|---|
| PH-16 | In-house cost figures for the target market (salaries per role) |
| PH-17 | Founder photos (2) + 1-line bios |
| PH-18 | Founder story / mission (3–4 sentences) |
| PH-19 | Lead magnet: title, 1-line pitch, cover image, the PDF itself |
| PH-21 | Answers to 5 new FAQs |

## Tools / technical
| ID | What | Options |
|---|---|---|
| PH-19 | Email tool for lead magnet form | MailerLite (free), ConvertKit, Tally |
| PH-22a | Form backend for qualification form | Tally (free), Formspree, GoHighLevel |
| PH-22b | Booking calendar embed | Calendly or Cal.com (both have free plans) |
| PH-23 | Share image (1200×630) at `/og-image.png` | Then uncomment the og:image tags in `<head>` |
| PH-24 | GA4 ID + Meta Pixel ID | Snippets are already in `<head>`, commented out |
| PH-25 | Domain email (hello@presenceuplift.com) | Google Workspace / Zoho |
| PH-26 | Real Privacy Policy + Terms | `privacy.html`, `terms.html` have outlines. Termly/iubenda can generate. Needed before ads or forms go live. |

## When everything is filled
- Remove the yellow draft bar at the top of `index.html`
- Remove `noindex` from `privacy.html` / `terms.html`
- Then we work on design, layout and the conversion flow
