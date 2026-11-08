# Santhosh & Lalli — Original Direct Invitation

## Homepage
`index.html` is the direct invitation landing page. Upload the contents of this folder to the root of your GitHub Pages repository.

## Preserved from your HTTrack download
- Original React/Vite application bundle and original rendering/animation/scroll logic
- Original CSS design and responsive styling
- 12 downloaded WebP images, including logo and invitation artwork
- `music.mp3`, `thumbnail.jpg`, and `favicon.svg`
- All 52 downloaded TTF font files, connected through `assets/local-fonts.css`

## Changes made (no redesign)
1. Kept the original app bundle and stylesheet.
2. Changed only the 12 `/assets/...` image paths and `/music.mp3` path in the bundle to relative paths (`./assets/...`, `./music.mp3`) so assets work on GitHub Pages project URLs as well as domain-root hosting. Animation, scrolling, and React logic were not rewritten.
3. Added a local font stylesheet after the original stylesheet so the captured font files are used locally. Manrope was not included in the HTTrack download; its local alias uses the downloaded Montserrat font as a close fallback.

## Two image assets still missing from the HTTrack capture
The original CSS references these two backgrounds at the original Netlify host, so they may still display while that source remains online. They are not local in this ZIP:
- https://indrajith-rebekah-wedding.netlify.app/assets/family-invitation-paper-DtXyzIjB.webp
- https://indrajith-rebekah-wedding.netlify.app/assets/family-invitation-paper-v2-CXcp8vkD.webp

To make the mirror fully self-contained, include those two exact URLs in a new HTTrack run and send the new ZIP.

## Editing invitation wording
As requested, no `invite-data.js` or separate editor was added. Use Find (Cmd+F) in `assets/index-szroeMAA.js` to replace the original couple names, date, venue and text. The JS bundle is minified into one line. Keep a backup before editing.

## Test locally
Open the folder in VS Code and use Live Server on `index.html`. Test the opening, sound button, full scroll and all sections. The sound button may require a user tap because browsers block autoplay until interaction.

## GitHub Pages
Upload the *contents* of this folder, not the outer folder itself. `index.html` must be at the repository root. Keep `assets/` and `music.mp3` in their current locations.
