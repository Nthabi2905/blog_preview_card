# Blog preview card — solution

This project is a responsive implementation of the "Blog preview card" challenge.

Files of interest

- HTML: [index.html](index.html)
- CSS: [styles.css](styles.css)
- Style reference: [style-guide.md](style-guide.md)
- Original readme template: [README-template.md](README-template.md)

How to view

1. Open [index.html](index.html) in your browser (no build step required).
2. Replace the images in `assets/images/` with your preferred assets if needed:
   - mobile: `assets/images/image-header-mobile.jpg`
   - desktop: `assets/images/image-header-desktop.jpg`
   - avatar: `assets/images/avatar-michelle.jpg`

What I implemented

- Mobile-first layout that switches to a two-column (image + content) layout at 900px.
- Typography uses Figtree (weights 500 and 800) as specified in the style guide.
- Colors and spacing follow values from [style-guide.md](style-guide.md).
- Accessible hover and focus states for the Read more control.

Notes

- If local font files are preferred, you can replace the Google Fonts link in the head of [index.html](index.html) and load the files from `assets/fonts/`.
- The image filenames are the common ones used in this challenge; if your assets use different names, update the <picture> sources in [index.html](index.html).

Enjoy — open [index.html](index.html) to preview.
