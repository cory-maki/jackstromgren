Photo slots wired into the HTML:
- hero.jpg            -> homepage hero, about profile card, Person schema image
- hero-secondary.jpg  -> homepage about-teaser image
- article-1.jpg       -> dental-anxiety-clinical-issue.html hero + homepage card
- article-2.jpg       -> oral-appliance-therapy-sleep-apnea.html hero + homepage card
- article-3.jpg       -> executive-protection-dental-plan-pillars.html hero + homepage card

Photographs supplied September 2026. Each file is cut to the aspect ratio its
slot displays, so the CSS crop does not cut faces:
  hero.jpg           1200x1200  (shown in a 160px / 80px circle)
  hero-secondary.jpg 1200x1600  (.ha-photo is aspect-ratio 3/4)
  article-*.jpg      1200x800   (280px homepage card + article hero band)

To swap a photo: replace the file keeping the same filename and aspect ratio.
No HTML changes are required.
