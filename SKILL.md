---
name: sabrina-siu-design
description: Design or refine portfolio pages in the visual language of sabrinasiu.com. Use when the user asks to match Sabrina Siu's site, extend its design system, or review a page for fidelity to that style; do not apply it to unrelated designs.
---

# Sabrina Siu design language

Use this skill to carry the public site's visual language into new or revised pages. Match the site's restraint and editorial hierarchy while adapting the layout to the user's actual content and platform. The [home](https://www.sabrinasiu.com/), [personal](https://www.sabrinasiu.com/personal.html), and [work entrance](https://www.sabrinasiu.com/portfolio.php) pages are the source. The protected work content was not inspected.

## Core character

- Make the page feel like an editorial portfolio: generous white space, left-aligned content, sparse controls, and media as the focal point.
- Use black text on white, with vivid violet `#4100F4` for navigation, active state, and focused controls. Let project images supply most other color.
- Keep the language direct and personal. Explain the intent and making of work in concrete terms rather than using promotional copy.
- Avoid card-heavy layouts, shadows, decorative dividers, dense navigation, and multiple competing accent colors.

## Type and surfaces

- Use **Cormorant Garamond** for expressive text: navigation, the home introduction, section headings, and expanded-media titles. Use **Inter** for practical reading text, descriptions, and form controls. Provide sensible serif and sans-serif fallbacks.
- Prefer regular or semibold weights. Use serif italics selectively for a role line, a quiet introductory line, or a small caption.
- Reference scale: navigation 18px; home body 22px with 1.65 line height; interior body 16px with 1.7 line height; personal section headings about 38px on desktop and 29px on mobile. Preserve hierarchy rather than forcing these sizes into every context.
- Keep the general background white. On a home-like introduction, a soft lavender radial glow (`#C7BAED`) can drift toward the pointer beneath a subtle grain texture. The social icons there use pale lavender (`#B8A8E0`). Interior pages stay plain white.
- Use thin text underlines where links appear in body copy. Make hover feedback subtle, often a modest opacity change.

## Layout patterns

- Use an 80px horizontal page inset on desktop and 28px on screens at or below 768px. Allow generous vertical breathing room.
- Keep the top navigation fixed. On desktop, use a small lowercase serif link row with 24px gaps. The current link is fully opaque and semibold; other violet links are quieter. Interior pages use a near-white translucent navigation surface with a light blur.
- On mobile, use a three-line menu button aligned to the right. Open its links in a vertical list on a near-white blurred surface; morph the icon into an X. Keep its accessible name and expanded state accurate.
- For a home-like page, place a wide, left-aligned introduction beneath the navigation, with the name first, an italic role line next, and short paragraphs after. Leave open space around it. Small social links may sit at the upper right on desktop.
- For a personal-project gallery, pair sticky introductory text on the left with a two-column square media grid on the right. The observed desktop proportion is about `1fr 1.4fr`, with a 60px column gap and generous separation between sections. At 768px and below, stack the text above the grid and stop making it sticky.
- For a protected-work entrance, use a small left-aligned composition with a serif heading, italic explanation, a password field, and a solid black action button. Keep the controls square-cornered and stack them on mobile.

## Media and interaction

- Give project thumbnails square crops, a subtle 4px radius, a 12px grid gap, and a light-gray fallback surface. Favor real project photography or video over decorative illustrations.
- On hover, enlarge thumbnail media only slightly (about `scale(1.03)` over 0.4s). Reveal gallery sections with a restrained fade and upward movement (about 0.8s); the media can follow with a small delay.
- Let silent looping video previews play while visible and pause when out of view. Respect user and browser motion or autoplay preferences when implementing new pages.
- Open gallery media in a nearly opaque white lightbox with a large contained image or video, serif title, readable description, and quiet close control. Support closing by the control, Escape, and the backdrop; maintain keyboard access and focus.
- If using the home pointer glow, make it follow with easing rather than snapping directly to the cursor. Keep the effect decorative and out of the way of text and controls.

## Content structure

- Group personal projects by practice or theme. Introduce each group with a short title and one concise framing description.
- Pair each item with specific, human descriptions of inspiration, materials, process, or outcome. Keep image alt text and icon link names meaningful.
- Treat the exact page content and media as examples of structure, not reusable filler. Adapt the design to the user's own work and goals.

When reviewing an implementation, prioritize the page's overall restraint, serif/sans pairing, violet navigation, spacing, and media presentation before tuning small motion details.
