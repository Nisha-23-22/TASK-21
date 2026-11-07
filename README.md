# OmniFood - Responsive Food Delivery Landing Page

## Project overview

A responsive, single-page landing website for a food delivery brand ("Omnifood"), built with **HTML and CSS only** (no JavaScript, no Bootstrap or Tailwind). The page has six sections:

1. **Header + Hero** - circular logo, navbar (FOOD DELIVERY, HOW IT WORKS, OUR CITIES, SIGN-UP), headline "GOODBYE JUNK FOOD / HELLO SUPER HEALTHY FOOD", two buttons ("I'm Hungry" and "Show me more") and a background image with a dark overlay.
2. **How it works** - phone mockup on the left, three numbered steps on the right, and Google Play / App Store buttons below the steps.
3. **Our cities** - "WE'RE CURRENTLY IN THESE CITIES" with four city cards (Lisbon, London, Berlin, San-Francisco), each with an image, name and details (happy eaters, chefs, handle).
4. **Testimonials** - "OUR CUSTOMER CAN'T LIVE WITHOUT US" with three quotes, avatars and names on a background image with a dark overlay.
5. **Pricing plans** - "START EATING HEALTHY TODAY" with Premium ($399 / month), Pro ($199 / month) and Starter (19$ / meal) cards, feature lists with check and cross icons, and Sign up buttons.
6. **Footer** - links on the left (About us, Blog, Press, iOS App, Android App), social icons on the right and a copyright line.

## Folder structure

```
OmniFood/
|-- index.html
|-- style.css
|-- README.md
`-- assets/        (logo, hero and testimonial backgrounds, city images, phone mockup, avatars)
```

## How to run

Just open `index.html` in a browser. No build step or server is needed. (An internet connection is only used to load the Lato font from Google Fonts. Without it the page falls back to a system font.)

## Responsive breakpoints used

| Screen | Breakpoint | Layout |
| --- | --- | --- |
| Desktop | 1200px and above | Full layout: 4-column cities grid, 3-column testimonials and pricing, steps next to the phone |
| Small laptop | up to 1199px | Slightly smaller headline and tighter grid gaps |
| Tablet | up to 834px | Sections stack (phone above the steps); cities, testimonials and pricing become 2 columns |
| Mobile | up to 480px (covers 390px) | Single column everywhere; navbar collapses into a hamburger menu (pure CSS checkbox toggle); buttons stack |

The page has no horizontal scrolling, images scale with `max-width: 100%`, and text and buttons stay aligned and readable at every size.

## Notes

- Images in `assets/` (hero food, city scenes, phone, avatars, logo) are illustrations created for this project. Replace them with real photos of the same file names if you want to match the original screenshots more closely.
- The Google Play and App Store buttons are plain styled buttons and contain no official brand logos.
- Social icons and links are placeholders.
