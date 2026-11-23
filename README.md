# Nathaniel's portfolio

A static cybersecurity student portfolio. No framework, package installation, or build step is required.

## Open locally

Open `public/index.html` directly in a browser. Fonts and project artwork are stored locally. Repository and profile links require internet access. Email links open Gmail's compose page with `nathantapar@gmail.com` prefilled; visitors may need to sign in to Gmail.

For a local HTTP preview, open a terminal in this folder and run:

```sh
python -m http.server 4173 --bind 127.0.0.1 --directory public
```

Then open http://127.0.0.1:4173/.

## Edit

- `public/index.html`: biography, education, coursework, certificate summaries, and contact email.
- `public/styles.css`: colors, typography, spacing, and responsive layouts.
- `public/assets/`: project artwork and locally hosted IBM Plex fonts with their license.

The site lists individual online course completions and features [Lantern](https://github.com/NathanTapar/Lantern), a local network assessment app. Its screenshot uses fictitious sample data and comes from that repository's documentation; the source MIT license is included as `assets/lantern-LICENSE.txt`.

## Hosting and privacy

Publish **only the `public` folder**, never this parent folder. The parent `certificates/` folder retains PDF copies and must stay outside the website's document root. Original certificates also remain in the separate source folder.

The public site contains reduced-resolution, watermarked certificate previews with titles, issuers, and completion dates. Printed verification URLs are masked. Previews are non-interactive and dragging is disabled. No original certificate PDFs or external credential links are included.

These controls discourage casual copying; they cannot prevent screenshots, saved page resources, or someone retrieving an image URL. The project screenshot is also non-interactive.

The root HTML/CSS files are retained as a backup. Make future website edits in `public/`. The portfolio has not been deployed to the internet.
