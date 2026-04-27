# FRC Team Website

This is a static website for Luban Robotics, FRC Team 9597. Open `index.html` in a browser to view it.

## Quick Edits

- Team name and number: search for `Luban Robotics` and `9597` in `index.html`.
- Logo: replace the `.brand-mark` text or swap it for an image in the two `.brand` blocks.
- Engineering notebook cards: edit the `#notebook` section in `index.html`.
- Photos: replace each `.image-placeholder` figure with an image, for example:

```html
<img src="images/robot.jpg" alt="Team robot scoring during a match" />
```

- Sponsors: replace or add logo images in `images/sponsors/`, then update the sponsor grid in `index.html`.
- Blog posts: edit the cards in the `#blog` section.
- Contact links: update the email and social links in the `#contact` section.

## Suggested Image Folders

Create these folders when you add real media:

- `images/robot/`
- `images/team/`
- `images/competitions/`
- `images/notebook/`
- `images/sponsors/`

## Files

- `index.html` - page content and section structure
- `styles.css` - colors, layout, cards, mobile styles
- `script.js` - mobile menu and contact form placeholder behavior
- `images/notebook/` - extracted notebook images used in engineering cards
