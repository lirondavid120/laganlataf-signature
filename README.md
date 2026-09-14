# laganlataf-signature

Public image assets for the "לגן ולטף" (Lagan Lataf) HTML email signatures.

Files live in `img/` and are served over HTTPS via GitHub Pages:

    https://lirondavid120.github.io/laganlataf-signature/img/

## Current asset set

| File | Size | Used by |
|---|---|---|
| `laganlataf_logo.gif` | 300x101, 48 frames | option 1 (logo beside details), original signature |
| `laganlataf_logo_400.gif` | 400x135, 48 frames | option 2 (logo above details) |
| `ic_mobile.png` | 56x56, shown at 20x20 | phone rows |
| `ic_mail.png` | 56x56, shown at 20x20 | email row |
| `ic_web.png` | 56x56, shown at 20x20 | website row |
| `ic_pin.png` | 56x56, shown at 20x20 | address row (option 2 only) |

Both GIFs have their complete logo as frame 1 on purpose, so Outlook desktop —
which renders only the first frame of an animated GIF — still shows the full logo.

## Legacy names (do not delete)

`icon_mail.png`, `icon_phone.png` and `icon_web.png` are the same images as
`ic_mail.png`, `ic_mobile.png` and `ic_web.png` under their original filenames.
The first version of the signature references the old names and may already be
installed in a mail client, so these are kept so that previously sent mail keeps
rendering.

## Rules

Do not re-encode, compress, resize or convert these files, and do not rename or
remove them. Email clients fetch them by URL at read time, so any change is
retroactive across every message already sent.

`.nojekyll` disables Jekyll processing so files are served verbatim.
`.gitattributes` marks the images binary so git never applies text conversion.
