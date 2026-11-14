# Media and Typography Starter

Use this small page for Module 4 practice if you do not want to use your capstone yet.

## Files

- `index.html`: sample content with media and typography tasks.
- `styles.css`: starter CSS with tokens and prompts.
- `assets/sample-icon.svg`: simple SVG for accessibility treatment practice.

## Practice goal

Build a media and typography optimization pass:

- responsive image markup
- dimensions or aspect-ratio protection
- SVG treatment
- typography tokens
- fluid type or spacing
- font fallback strategy
- zoom and slow-network notes

The starter uses placeholder image paths so you can replace them with your own exported image variants.

## Responsive Image Placeholder Plan

I chose to leave the supplied garden workshop placeholder remains in place because I
have not selected a photograph or exported image variants yet.

Before replacing the placeholder, I will be sure to:
- Select a garden workshop photograph and document its source.
- Export matching 3:2 crops at 480 × 320, 960 × 640, and 1440 × 960 pixels.
- Compare image quality and file sizes before choosing the final format.
- Add srcset with width descriptors and sizes matching the layout:
- full-width within the wrapper when stacked, and approximately half the wrapper when the hero uses two columns.
- Include width and height attributes and retain the 3:2 aspect ratio so space is reserved before the image loads.
- Write alt text based on the selected photograph and its purpose.

## SVG Treatment

The supplied assets/sample-icon.svg is decorative beside the section
heading. Its image element uses empty alt text to avoid repeating
information.

## Media and Typography Decisions

- Media: I retained the supplied garden image placeholder and documented
  a responsive-image plan because photo variants are not available yet.
  The supplied SVG is decorative and uses empty alt text.
- Typography: Custom properties control body and heading fonts, text
  sizes, line heights, reading measure, and spacing. clamp() provides
  fluid heading sizing and section spacing.
- Layout-shift prevention: The image placeholder reserves a 3:2 aspect
  ratio. Explicit 48 × 48 SVG dimensions reserve space for the icon.

## Browser Checks

I checked the page in Chrome at narrow and wide viewport widths,
200% browser zoom, and simulated Slow 4G with caching disabled.
Screenshots in my evidence folder document these conditions. The 375 px, 1280 px and 200% zoom all passed the testing. 

The slow-network check covers the existing placeholder and SVG.
Actual responsive photo loading will need testing after image
variants are exported and added.

## AI Disclosure

I used ChatGPT to help explain syntax, generate some test prompts, and troublehsoot css. I reviewed the changes in the browser and collected
the testing screenshots myself.