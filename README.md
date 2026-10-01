# Mam Birthday Surprise ❤️

A mobile-first cinematic birthday surprise site for GitHub Pages.

## Folder structure
```text
mam-birthday-surprise/
├── index.html
├── README.md
└── images/
    ├── photo1.jpg  # Birthday reveal / Happy Birthday Mam ❤️
    ├── photo2.jpg
    ├── photo3.jpg
    ├── photo4.jpg
    ├── photo5.jpg
    └── photo6.jpg
```

## Login
Accepted User IDs (case-insensitive): Tuktuk, Uddav, Babu, Sir, Uddav Gupta
Password: `29/02/2024`

## Music
The site uses the YouTube video ID `zjYj7He5WCI` and requests playback from 00:15 after successful login. Browser autoplay rules can still block playback; if that happens, use the small **Tap to start** control in the music dock.

## Easy future edits
Open `index.html` and edit the `CONFIG` object near the bottom. To add more memories:
1. Put the new image inside `images/`.
2. Add its path to `MEMORY_PHOTOS`.
3. Optionally add a caption to `MEMORY_CAPTIONS`.

For a GitHub Pages deployment, upload the whole folder contents to the repository root and enable Pages from the repository's main branch/root folder.

Note: the login is a cute client-side entry lock, not real security. The password is visible in the site's JavaScript.
