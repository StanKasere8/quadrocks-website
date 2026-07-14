# Quadrocks Contracting — Project Log

## Session 1 — July 9, 2026

### Built
- `index.html` — full homepage per master design spec (nav, hero, statement bar, services, why-choose-us, stats, featured projects, safety/quality, leadership, testimonials, final CTA, footer)
- Design system: Manrope + Syne, navy/gold/cream/concrete palette, glassmorphism, grain texture, gold cursor glow, scroll reveals with stagger, animated counters, parallax hero, mobile overlay menu
- Signature visual motif: a four-diamond mark referencing the four founders behind "Quad," used near the logo and hero eyebrow

### Real assets integrated
- `assets/logo.png` — client logo, background removed for clean placement on dark navy header/footer
- `assets/site-photo-1.jpg`, `assets/site-photo-2.jpg` — real Quadrocks site photos (foundation brickwork), used in hero background, "Why Choose Us," and Featured Projects
- `assets/concept-home-1.jpg`, `concept-home-2.jpg`, `concept-home-3.jpg` — architectural render concepts, currently carrying a visible **"MG Design Solutions"** watermark

### Open item — action needed
⚠️ **Watermark on concept renders**: client confirmed using these for now, but wants unwatermarked/licensed versions later. **Before this site goes live, these need replacing** with either (a) clean versions from the rights holder, or (b) Quadrocks' own architectural renders. Tracked here so it isn't missed.

### Placeholder content still in use (client chose to draft-and-edit-later)
- Stats: 120+ projects, 15+ years, 250+ staff, 98% satisfaction
- Featured project names/categories (2 real photos are genuine; 2 concept renders are labeled "Concept")
- Leadership quotes for Mr. Tichaona Kasere and Mr. Stanley Kasere
- Testimonial names/companies
- Contact details in footer (phone, email are placeholder format)

### Next up
- about.html, services.html, projects.html, contact.html, careers.html, news.html
- Swap in real stats/testimonials/contact info once client provides them
- Replace watermarked renders once clean versions are available

## Session 2 — July 10, 2026

### Fixed on homepage
- CSS bug: `.four-mark span` selector was too broad and was hijacking the hero eyebrow text (shrinking + rotating it). Scoped to `.dot` class.
- Removed last remaining external Unsplash dependency (Final CTA background) — replaced with real local site photo. Page is now fully self-contained (no external image requests at all).

### Built
- `about.html` — company story (name origin woven in), mission & vision, 9 core values grid, full leadership bios (Tichaona & Stanley Kasere), safety culture, community commitment section

### Note
- Statistics section on homepage left as-is per client's request — client will comment it out and swap in real numbers themselves when ready.
