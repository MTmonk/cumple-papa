# Claude Code — Project Notes

## Project
Single-page birthday tribute website for Mario's 80th birthday, deployed via GitHub Pages. No build system — plain HTML/CSS/JS.

## Key decisions
- **Font**: Jost (Google Fonts) replaces Lato as the main sans-serif — closest open-source equivalent to Futura.
- **Poem**: Text extracted from `Auschwitz.docx`. Original layout is two-column; rendered as CSS grid (two columns on tablet+, single column on mobile).
- **Video**: `video1.mp4` embedded with native `<video>` element in a dark section after the photo gallery.
- **Music**: External MP3 from archive.org (public domain). Starts muted, unmutes on user interaction.

## Do not change
- Colour tokens in `:root` — the gold/cream/bark palette is intentional.
- The lightbox JS — it handles swipe, keyboard, and click navigation.
- The poem text — it was transcribed from the source `.docx` with correct UTF-8 Spanish characters.
